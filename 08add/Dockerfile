FROM  ubuntu 
RUN   apt update && apt install nginx -y
RUN  rm -rf /var/www/html
CMD   ["nginx","-g","daemon off;"]
EXPOSE 80
ADD  index.html /var/www/html/index.html

