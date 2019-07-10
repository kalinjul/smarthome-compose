FROM julakali/smarthome-ng:v1.6
RUN apt-get update && apt-get install -y python python-serial python-pip \
  && rm -rf /var/lib/apt/lists/*
RUN pip2 install broadlink
