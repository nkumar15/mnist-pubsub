FROM tensorflow/tensorflow:latest-gpu
COPY . /mnist/
WORKDIR "/mnist"
RUN pip install -r requirements.txt
ENTRYPOINT ["python", "-u", "main.py"]

