FROM python:3.8-slim

WORKDIR /app

COPY requirements.txt .

RUN python -m pip install --no-cache-dir -r requirements.txt

EXPOSE 5001

COPY . .

CMD ["python", "app.py"]