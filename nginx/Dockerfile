FROM nginx:1.27

COPY hackspace.conf /etc/nginx/conf.d/hackspace.conf
COPY proxypass.conf /etc/nginx/snippets/proxypass.conf
RUN mv /etc/nginx/conf.d/default.conf /etc/nginx/conf.d/default.conf.disabled
