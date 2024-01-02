FROM bitnami/kubectl:latest AS kubectl

FROM airbyte/worker:0.50.40
COPY --from=kubectl /opt/bitnami/kubectl/bin/kubectl /usr/local/bin/kubectl