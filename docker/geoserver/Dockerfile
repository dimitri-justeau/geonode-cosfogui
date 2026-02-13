ARG BASE_IMAGE_VERSION
FROM geonode/geoserver:${BASE_IMAGE_VERSION}

# FIX CVE-2025-15467
RUN apt-get update && apt-get install -y openssl