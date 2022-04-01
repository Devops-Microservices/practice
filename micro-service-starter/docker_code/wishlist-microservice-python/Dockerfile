FROM python:alpine3.15
LABEL maintainer="shrayansh"

WORKDIR /app

COPY . .

RUN pip install flask flask_cors

EXPOSE 1003

CMD ["python","index.py"]
