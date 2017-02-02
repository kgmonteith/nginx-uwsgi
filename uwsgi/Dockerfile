FROM ubuntu:latest

RUN apt-get update && apt-get install -y \
	python \
	python-dev \
	python-pip \
  && rm -rf /var/lib/apt/lists/*

RUN pip install --upgrade pip && pip install uwsgi

CMD ["uwsgi"]
