#build stage
FROM golang:alpine AS builder
ENV APP_HOME=/go/src/app
RUN apk add --no-cache git
WORKDIR $APP_HOME
COPY . .
RUN go get -d -v ./...
RUN go install -v ./...
RUN go build -o /out/app .
RUN ls

#final stage
FROM alpine:latest
RUN apk --no-cache add ca-certificates
COPY --from=builder ./out/app /app
EXPOSE 3000

ENTRYPOINT ./app
LABEL Name=codeboxgo Version=0.0.1
EXPOSE 3000

# Docker build
# docker build -f hello-world/Dockerfile hello-world/ -t hello-world:go
# docker run -p 3000:3000 hello-world:go