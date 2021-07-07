FROM python:3.8-slim
ADD . /app
COPY ./requirements.txt /app
WORKDIR /app
RUN pip install -r requirements.txt
ENV PYTHONPATH /app
