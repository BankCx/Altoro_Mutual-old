FROM checkmarx.jfrog.io/engines-docker/dast-cli:test

COPY entrypoint.sh /entrypoint.sh

RUN chmod +x /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]
