FROM python:3.6
WORKDIR /app

COPY requirements.txt /app
COPY my_model.h5 /app

RUN pip install -r ./requirements.txt

COPY app.py /app
CMD ["python", "app.py"]~
