FROM  ubuntu 
RUN   apt update && apt install nginx -y
RUN  rm -rf /var/www/html
CMD   ["nginx","-g","daemon off;"]
LABEL   owner="zelarsoft"\
        maintainer="devteam"\
        projectname="devops"
EXPOSE 80
COPY html /var/www/html