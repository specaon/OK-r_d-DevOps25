FROM python:3.9-slim
WORKDIR /Úkol2
COPY calculator.py .
COPY test_calculator.py .
RUN python -m unittest test_calculator.py -v
CMD ["python", "calculator.py"]