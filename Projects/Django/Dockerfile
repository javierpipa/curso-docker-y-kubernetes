FROM python:3
ENV PYTHONUNBUFFERED=1
WORKDIR /code
COPY requirements.txt /code/
RUN pip install -r requirements.txt
COPY . /code/
RUN django-admin startproject composeexample .
# COPY ./settings.py /code/composeexample/
RUN python manage.py migrate