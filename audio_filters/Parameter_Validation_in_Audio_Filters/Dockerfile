# Dockerfile for running parameter validation tests
FROM python:3.10-slim
WORKDIR /app
COPY .. .
RUN pip install pytest numpy
CMD ["pytest", "parameter_validation_test.py"]