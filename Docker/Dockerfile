FROM python:3.8.19-bullseye

COPY . /code
RUN apt-get update && apt-get install -y libhdf5-dev
RUN pip install --upgrade pip \
    && pip install -r /code/requirements.txt
