FROM python:3.9

WORKDIR /app

COPY main.py /app

RUN pip install fastapi[all] uvicorn sqlalchemy

EXPOSE 8000

CMD ["uvicorn", "main:app", "--host", "0.0.0.0", "--port", "8000"]
