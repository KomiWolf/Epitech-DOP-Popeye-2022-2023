FROM python:latest
WORKDIR /poll
EXPOSE 80
COPY requirements.txt .
RUN pip3 install -r requirements.txt
COPY . .
CMD ["flask", "run", "--host=0.0.0.0", "--port=80"]
