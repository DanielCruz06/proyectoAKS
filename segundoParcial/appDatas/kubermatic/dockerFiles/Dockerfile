FROM python:3.6
WORKDIR /app
COPY requirements.txt /app
RUN pip install -r ./requirements.txt
COPY app.py /app
EXPOSE 5000
CMD ["python", "app.py","--host","0.0.0.0","--port","5000"]