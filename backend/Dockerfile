
FROM python:3.10-slim
WORKDIR /app
COPY main.py .
RUN pip install fastapi uvicorn openai
CMD ["uvicorn", "main:app", "--host", "0.0.0.0", "--port", "8000"]
