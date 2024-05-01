FROM python:3.11

COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

COPY . /app

WORKDIR /app

EXPOSE 5001

CMD ["python", "app.py"]
