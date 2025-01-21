FROM python:3.14.0a4

WORKDIR /app

COPY requirements.txt .

RUN pip3 install -r requirements.txt 

COPY . .

EXPOSE 5000

CMD ["flask", "run", "--host=0.0.0.0"]

