FROM run:v1
RUN rm -rf /usr/share/nginx/html/index.html
COPY sample-html-files-sample2.html/ /usr/share/nginx/html/
CMD ["nginx", "-g" , "daemon off;"]