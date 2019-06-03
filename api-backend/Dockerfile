FROM ubuntu:latest

RUN apt update
RUN apt install -y python python-requests python-flask

COPY api.py /bin

CMD ["/usr/bin/python", "/bin/api.py"]
