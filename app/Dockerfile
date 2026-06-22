FROM nginx:alpine 
COPY index.html /usr/share/nginx/html/index.html 
RUN sed -i 's/listen       80;/listen 8080;/g' /etc/nginx/conf.d/default.conf 
#PORT 80
CMD ["nginx","-g","daemon off;"] 
EXPOSE 8080 
