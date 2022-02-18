FROM python:3.8

WORKDIR /app

COPY ./techtrends .

RUN pip3 install -r requirements.txt

RUN python init_db.py

EXPOSE 3111

CMD python app.py