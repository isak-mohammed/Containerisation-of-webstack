FROM nginx
LABEL "Project"="containerisation_of_webstack"
LABEL "Author"="Isak"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY mynginx.conf /etc/nginx/conf.d/mynginx.conf