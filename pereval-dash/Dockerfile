FROM nginx:1.10

RUN apt-get update && apt-get install -y git 

RUN cd /usr/share/nginx/html && git clone  https://github.com/pereval-team/pereval-dash.git


EXPOSE 9090
