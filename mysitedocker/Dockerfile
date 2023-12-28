FROM python:3
ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONUNBUFFERED=1
WORKDIR /code
COPY requirements.txt /code/
COPY django-polls-0.1.tar.gz /code/
RUN pip install -r requirements.txt
RUN pip install django-polls-0.1.tar.gz
COPY . /code/