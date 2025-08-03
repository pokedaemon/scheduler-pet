# is builder stage that install all dependencies n build our backend
# NOT FINISHED
FROM rust:latest AS builder 
WORKDIR /usr/src/scheduler
COPY . .
RUN cargo install --path .

CMD ["scheduler-back"]
