FROM ubuntu:latest
RUN apt-get update && apt-get upgrade -y
# Install python3 and python3-pip
RUN apt-get install -y python3 python3-pip
RUN rm /usr/lib/python*/EXTERNALLY-MANAGED
# Install Flask
RUN pip3 install flask
WORKDIR /app
COPY api.py /app/api.py
# Run the Flask app when the container starts
CMD ["python3", "api.py"]
