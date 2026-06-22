FROM almalinux:9
RUN dnf install git nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
RUN git clone https://github.com/jamamjadalone/50-html-css-js-projects /tmp/projects
RUN cp -r /tmp/projects/* /usr/share/nginx/html
CMD ["nginx","-g","daemon off;"]