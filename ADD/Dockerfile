FROM run:v1
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://toolsfairy.com/code-test/sample-html-files# /usr/share/nginx/html/
CMD ["nginx", "-g" , "daemon off;"]