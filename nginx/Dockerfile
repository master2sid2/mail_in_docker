FROM	alpine:3.10.2

RUN	apk add --update nginx && \
	mkdir -p /run/nginx/

WORKDIR /var/www/

EXPOSE	18080 18443
CMD	["nginx", "-g", "daemon off;"]
