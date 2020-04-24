FROM nginx:1.17.0
LABEL maintainer 'Alexandre Operand <devs at operand.com.br>'
RUN echo '<h1>Hello World - Alexandre</h1>' > /usr/share/nginx/html/index.html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
