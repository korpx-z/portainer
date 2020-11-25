FROM quay.io/ibmz/alpine:3.12

COPY dist/ /dist/

VOLUME /data
WORKDIR /

EXPOSE 9000
EXPOSE 8000

ENTRYPOINT ["/portainer"]
