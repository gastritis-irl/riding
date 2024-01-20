FROM python:3.11

WORKDIR /app

COPY . .

RUN pip install --no-cache-dir -r requirs.txt

EXPOSE 7403

CMD ["python", "kerasdep.py"]
