#installing OS(image) what you need
FROM ubuntu:18.04
#updating ubuntu OS(image) 
RUN apt-get update -y
#installing app environment(java). you can install app whatever you need
RUN apt-get install default-jre -y
#creating path that your app run here.If path doesnt exist, that path will create auto.
WORKDIR /merhaba
#copying source code from "myapp" to "WORKING" directory
COPY /myapp .
#this works your app whit this command
CMD ["java",  "merhaba"]
#when you done with creating Dockerfile save
#then run docker build <imageName>
#create a container docker run <imageName>
#here is your application live and accessible