FROM python:2.7
COPY app.py app.py
COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt
EXPOSE 5000
ENTRYPOINT ["python","app.py"]
