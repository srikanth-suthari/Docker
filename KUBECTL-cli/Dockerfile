FROM alpine:latest
RUN apk add --no-cache curl
RUN curl -LO "https://k8s.io(curl -L -s https://k8s.io)/bin/linux/amd64/kubectl"
RUN  install -o root -g root -m 0755 kubectl /usr/local/bin/kubectl
ENTRYPOINT ["kubectl"]
