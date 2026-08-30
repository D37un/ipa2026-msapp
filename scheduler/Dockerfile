FROM python
WORKDIR /home/scheduler
COPY ./requirements.txt /home/scheduler/
RUN pip install -r requirements.txt
COPY ./*.py /home/scheduler/
CMD ["python", "/home/scheduler/scheduler.py"]
CMD ["python", "-u", "/home/scheduler/scheduler.py"]