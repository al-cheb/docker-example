FROM python:latest
RUN apt-get update && apt-get install iputils-ping dnsutils -y
ADD client.py /client/
WORKDIR /client/
