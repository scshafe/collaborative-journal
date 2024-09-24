# syntax=docker/dockerfile:1
# FROM python:3
# ENV PYTHONDONTWRITEBYTECODE=1
# ENV PYTHONUNBUFFERED=1
# WORKDIR /code
# COPY requirements.txt /code/
# RUN pip install -r requirements.txt
# COPY . /code/


# edited version below (above copied from online)

FROM python:3
ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONUNBUFFERED=1

# create a directory in the python-image (which is a docker image)
WORKDIR /code

# copy the contents of this directory 'backend' into the `/code/` python-image directory
COPY . /code/

RUN pip install -r requirements.txt

