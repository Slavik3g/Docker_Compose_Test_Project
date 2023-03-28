FROM python:3.10

MAINTAINER Slava Chebotarev 'slavik3g@gmail.com'

COPY .. /app

WORKDIR /app

RUN pip install -r requirements.txt

CMD ["python", "app.py"]