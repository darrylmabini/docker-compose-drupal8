FROM mysql:5.7

COPY healthcheck.sh /usr/local/bin/healthcheck
RUN chmod +x /usr/local/bin/healthcheck

HEALTHCHECK CMD ["healthcheck"]
