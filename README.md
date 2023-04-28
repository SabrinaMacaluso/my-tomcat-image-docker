# my-tomcat-image-docker


docker build -t mytomcatimage .

docker run -d --name mytomcat-server -p 8080:8080 mytomcatimage

docker exec -it mytomcat-server /bin/bash
