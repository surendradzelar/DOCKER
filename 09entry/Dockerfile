FROM  ubuntu 
RUN   apt update && apt install iputils-ping -y
CMD ["ping","-c","2"]
ENTRYPOINT   ["ping","-c","2"]
CMD     ["google.com"]
LABEL   owner="zelarsoft"\
        maintainer="devteam"\
        projectname="devops"
EXPOSE 80
