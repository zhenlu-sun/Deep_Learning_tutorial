FROM ubuntu:20.04

RUN apt-get update && apt-get install -y python3 python3-pip

WORKDIR /app/recurrent_neural_network
COPY . .
RUN pip3 install -r requirements.txt

CMD ["python3", "language_model.py"]