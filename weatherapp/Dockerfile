FROM python:3.6
LABEL maintainer "velugu srikanth"
ADD . /home/app
WORKDIR /home/app
RUN pip install -r requirements.txt
EXPOSE 5002
ENTRYPOINT ["python","app.py"]
CMD ["python","tables.py"]
