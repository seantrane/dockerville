# https://hub.docker.com/_/elasticsearch
FROM elasticsearch:5

COPY docker-healthcheck /usr/local/bin/

HEALTHCHECK \
  --interval=3m33s \
  --timeout=9s \
  --start-period=60s \
  --retries=3 \
  CMD ["docker-healthcheck"]
