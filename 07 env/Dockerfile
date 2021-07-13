FROM ubuntu
RUN apt update && apt install nginx -y
CMD ["nginx","-g","daemon off;"]
LABEL Owner = "zelarsoft"\
      maintainer = "DEV TEam"\
      projectname = "Devops"
EXPOSE 80
ENV URL=google.com
ENV project=zel