FROM resin/rpi-raspbian:jessie

RUN curl -fsSL http://repo.mosquitto.org/debian/mosquitto-repo.gpg.key | apt-key add -
RUN echo "deb http://repo.mosquitto.org/debian jessie main" >> /etc/apt/sources.list
RUN apt-get update && apt-get install -y mosquitto

CMD ["mosquitto"]
