FROM python:3
ENV PYTHONUNBUFFERED
WORKDIR /usr/src/app
COPY requirements.txt ./
RUN python -m pip install -r requirements.txt
COPY main.py .
EXPOSE 5000
CMD ["python", "main.py"]
