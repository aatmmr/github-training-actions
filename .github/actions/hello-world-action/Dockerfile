FROM alpine:3.10

COPY entrypoint.sh /entrypoint.sh

COPY $GITHUB_WORKSPACE /source-code

RUN chmod +x entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]
