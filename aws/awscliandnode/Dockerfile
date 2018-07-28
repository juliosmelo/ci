FROM node:6.9.4

RUN apt-get update
RUN apt-get install -y python-dev
RUN curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
RUN python get-pip.py
RUN pip install awscli

