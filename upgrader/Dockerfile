FROM debian:12.6
RUN apt update && apt install -y curl && curl -LO https://dl.k8s.io/release/v1.28.4/bin/linux/amd64/kubectl && chmod +x kubectl
COPY upgrader /
