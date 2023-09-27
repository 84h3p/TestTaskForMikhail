FROM ubuntu:latest
RUN apt update -y
RUN apt install -y python3-pip build-essential
COPY . /app
WORKDIR /app
RUN pip3 install -r requirements.txt
EXPOSE 8080
ENTRYPOINT ["python3"]
CMD ["app.py"]
