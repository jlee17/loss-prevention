FROM python:3.13-slim

WORKDIR /

COPY requirements.txt .

RUN pip install --no-cache-dir -r requirements.txt

COPY parser-publisher.py parser-publisher.py

CMD ["python3", "-u", "parser-publisher.py", "-f", "sample-file.txt"]
