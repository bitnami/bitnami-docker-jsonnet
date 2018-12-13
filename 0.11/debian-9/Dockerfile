FROM bitnami/minideb-extras:stretch-r221
LABEL maintainer "Bitnami <containers@bitnami.com>"

# Install required system packages and dependencies
RUN install_packages libc6 libgcc1 libstdc++6
RUN bitnami-pkg install jsonnet-0.11.2-0 --checksum fe79f9393bf581f31cb818f15dd94a8521cb3a0688c634e6e9883a5538ee9600

COPY rootfs /
ENV BITNAMI_APP_NAME="jsonnet" \
    BITNAMI_IMAGE_VERSION="0.11.2-debian-9-r2" \
    PATH="/opt/bitnami/jsonnet/bin:$PATH"

ENTRYPOINT [ "/app-entrypoint.sh" ]
CMD [ "nami", "start", "--foreground", "jsonnet" ]
