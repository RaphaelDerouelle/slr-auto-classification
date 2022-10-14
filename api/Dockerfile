FROM python:3.10
RUN mkdir /root/backend
WORKDIR /root/backend
COPY requirements.txt requirements.txt
RUN pip install --upgrade pip && \
    pip install -r requirements.txt
COPY . .