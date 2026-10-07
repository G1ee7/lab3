FROM python:3.12-slim
WORKDIR /app

COPY requirements.txt .
RUN pip install -r requirements.txt

COPY . .

ENV GREETING=Hello
ENV STUDENT=student
ENV VARIANT=0

EXPOSE 5000

CMD ["python", "app.py"]
