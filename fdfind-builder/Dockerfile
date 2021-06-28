FROM rust:alpine AS build
RUN cargo install fd-find

#FROM alpine:latest
#COPY --from=build /usr/local/cargo/bin/fd /usr/local/bin/fd

# Install and get fd as follows
# $ docker build -t fd-builder:0.1 .
# $ docker run -it -d --rm --name fd-builder fd-builder:0.1
# $ docker cp fd-builder:/usr/local/cargo/bin/fd .
# $ docker stop fd-builder
# $ docker rmi fd-builder:0.1

