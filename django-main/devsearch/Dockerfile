FROM python:3.8

ENV PYTHONUNBUFFERED 1

WORKDIR /home/ubuntu/Adil-Ilyas/actions-runner/_work/adil-ilyas/adil-ilyas

COPY . .

RUN python -m pip install --upgrade pip setuptools wheel

RUN pip install -r requirements.txt
