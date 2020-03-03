ARG TAG=1.17-alpine

FROM nginx:$TAG

LABEL mantainer="antonino.pecoraro@casavo.com"
LABEL description="Nginx Container"

# ADD data in image when build
ADD ./vhosts.conf /etc/nginx/conf.d/default.conf
