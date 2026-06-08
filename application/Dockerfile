FROM python:3.12.13-alpine3.23

RUN mkdir -p /var/flaskapp

WORKDIR /var/flaskapp

COPY . .

RUN pip install -r requirements.txt

EXPOSE 5000

CMD ["python", "app.py"]
