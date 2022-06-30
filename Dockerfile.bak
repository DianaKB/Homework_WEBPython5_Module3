FROM python:latest

MAINTAINER diana_kovalchuk "dianakovalhyk@ukr.net"

COPY . /personal-helper-bot-2

WORKDIR /personal-helper-bot-2

COPY requirements.txt .
RUN pip install -r requirements.txt

ENTRYPOINT ["python"]
CMD ["main.py"]
