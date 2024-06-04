FROM python3.9-alpine

RUN pip install -r requirements.txt

COPY app.py .

ENV FLASK_APP=app.py

CMD ["flask", "run", "--host=0.0.0.0"]
