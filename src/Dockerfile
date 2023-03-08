# syntax=docker/dockerfile:1

FROM public.ecr.aws/docker/library/python:3.8

WORKDIR /flask-app

COPY flask-app/requirements.txt requirements.txt
RUN pip3 install -r requirements.txt

COPY flask-app/ .

CMD [ "python3", "app.py"]
