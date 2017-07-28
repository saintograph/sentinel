FROM ubuntu:16.04

RUN apt-get update
RUN apt-get install -y python
RUN apt-get install -y python-pip
RUN pip install flask

COPY main.py /tmp/main.py

EXPOSE 5000

CMD ["python","/tmp/main.py"]