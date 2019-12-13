FROM	alpine:3.10.2

RUN	apk add --update nginx && \
	mkdir -p /run/nginx/

WORKDIR /var/www/

CMD	["nginx", "-g", "daemon off;"]
