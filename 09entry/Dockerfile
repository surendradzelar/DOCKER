FROM  ubuntu 
RUN   apt update && apt install iputils-ping -y
ENTRYPOINT   ["ping","-c","2"]
CMD     ["google.com"]
LABEL   owner="zelarsoft"\
        maintainer="devteam"\
        projectname="devops"
EXPOSE 80
