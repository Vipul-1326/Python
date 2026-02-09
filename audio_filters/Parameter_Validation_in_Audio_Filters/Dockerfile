FROM python:3.10-slim

WORKDIR /app

RUN pip install --no-cache-dir pytest numpy

COPY . .

RUN chmod +x test.sh

ENTRYPOINT ["./test.sh"]