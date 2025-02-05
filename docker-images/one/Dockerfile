FROM            docker.io/redhat/ubi8
run             dnf install nginx -y
ENTRYPOINT      ["nginx", "-g", "daemon off;"]
EXPOSE          80