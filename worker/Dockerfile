FROM python
WORKDIR /home/worker
COPY ./requirements.txt /home/worker/
RUN pip install -r requirements.txt
COPY ./*.py /home/worker/
CMD ["python", "-u", "/home/worker/worker.py"]