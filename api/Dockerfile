FROM python

WORKDIR /app

COPY ./app ./app
COPY requirements.txt ./

EXPOSE 5000

RUN pip install -r ./requirements.txt

CMD ["python", "-m", "flask", "run", "--host=0.0.0.0"]