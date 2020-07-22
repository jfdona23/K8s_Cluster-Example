FROM python:3

WORKDIR /usr/src/app

COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt

COPY hello.py ./
COPY static ./
COPY templates ./

ENV ENVIRONMENT=DEV HOST=localhost PORT=8000 REDIS_HOST=localhost REDIS_PORT=6379 REDIS_DB=0

EXPOSE $PORT

CMD [ "python", "./hello.py" ]