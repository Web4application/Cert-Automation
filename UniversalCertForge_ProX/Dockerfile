FROM python:3.11
WORKDIR /app
COPY . .
RUN pip install -r requirements.txt
CMD ["uvicorn", "web.main:app", "--host", "0.0.0.0", "--port", "8000"]
