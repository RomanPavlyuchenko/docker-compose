FROM python:3.8.10-slim
WORKDIR /app/
COPY . .
RUN pip install -r requirements.txt
CMD python3 manage.py collectstatic && python3 manage.py migrate
