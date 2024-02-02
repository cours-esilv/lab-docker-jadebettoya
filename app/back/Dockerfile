FROM python:3.8

WORKDIR /app/back

COPY . /app/back

RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 5000

ENV NAME TD3_ML

CMD ["python3", "-m", "flask", "run", "--host=0.0.0.0"]
