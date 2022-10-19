FROM checkmarx.jfrog.io/engines-docker/dast-cli:test_6

COPY entrypoint.sh /entrypoint.sh

RUN chmod +x /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]
