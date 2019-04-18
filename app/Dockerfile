FROM python:3.6

EXPOSE 5000

WORKDIR /app

COPY . /app
RUN pip install -r requirements.txt

ENV FLASK_APP=run.py

EXPOSE 5000
CMD [ "python", "-m", "flask", "run", "--host=0.0.0.0" ]
