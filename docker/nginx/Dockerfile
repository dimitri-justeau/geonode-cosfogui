ARG BASE_IMAGE_VERSION
FROM geonode/nginx:${BASE_IMAGE_VERSION}

# FIX CVE-2025-15467
RUN apk add --update --no-cache openssl