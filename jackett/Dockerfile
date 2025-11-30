ARG BUILD_FROM
FROM $BUILD_FROM

ARG TEMPIO_VERSION BUILD_ARCH
RUN \
   && JACKETT_RELEASE=$(curl -sX GET "https://api.github.com/repos/Jackett/Jackett/releases/latest" \
   && curl -o /tmp/jackett.tar.gz -L "https://github.com/Jackett/Jackett/releases/download/${JACKETT_RELEASE}/Jackett.Binaries.Linux${ARCH}.tar.gz" 


COPY rootfs /
