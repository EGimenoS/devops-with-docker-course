FROM ubuntu:18.04
RUN apt update && apt upgrade 
RUN apt install -y curl
WORKDIR /usr/src/app
COPY script.sh .
RUN chmod +x script.sh
CMD ./script.sh