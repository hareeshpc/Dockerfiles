FROM rust:alpine AS build
RUN cargo install fd-find

# Install and get fd as follows
# $ docker build -t fd-builder:0.1 .
# $ docker run -d --rm --name fd-builder fd-builder:0.1 
# $ docker cp fd-builder:/usr/local/cargo/bin/fd .
# $ docker stop fd-builder

