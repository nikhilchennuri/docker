# FROM almalinux:9
# RUN dnf install nginx -y
# RUN rm -rf /usr/share/nginx/html/index.html
# COPY index.html /usr/share/nginx/html/index.html
# CMD ["nginx","-g","daemon off;"]






FROM alamlinux:9
RUN dnf intall nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://github.com/jamamjadalone/50-html-css-js-projects/blob/main/index.html /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]