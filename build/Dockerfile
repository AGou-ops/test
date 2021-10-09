FROM debian:latest
RUN apt update \
    && apt install -y --no-install-recommends \
        curl \
        nginx \
    && systemctl start nginx
EXPOSE 80
