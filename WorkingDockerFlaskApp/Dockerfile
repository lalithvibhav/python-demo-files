FROM python:3.8.0-buster

# current working directory 
WORKDIR /app

COPY requirements.txt .
RUN pip install -r requirements.txt

COPY /app .

CMD ["python","botServer.py"]
