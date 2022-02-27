FROM python:3.7
COPY . /app 
WORKDIR /app 
RUN ["pip3", "install", "-r", "requirements.txt"]
EXPOSE 3030
ENTRYPOINT ["python3", "server.py"]
