# This is the docker file for the Custom Prometheus Docker Application Instrumentation

#FROM tiangolo/uwsgi-nginx-flask:python3.11

FROM tiangolo/uwsgi-nginx-flask:python3.8

RUN pip install prometheus_client

ENV LISTEN_PORT 5001

EXPOSE 5001

COPY ./app /app

WORKDIR /app