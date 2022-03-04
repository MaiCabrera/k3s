# Docker image for building the Go app
FROM golang:1-bullseye

WORKDIR /app
ADD . /app

RUN GO111MODULE=on go mod download
