FROM python:3.6.0-alpine

WORKDIR /app
ADD . /app

RUN apk --no-cache update && apk add --no-cache gcc=5.3.0-r0 libc-dev=0.7-r0 musl-dev && \
    pip install -r /app/requirements.txt && \
    apk del gcc libc-dev musl-dev

ENV POST_DATABASE_HOST post_db
ENV POST_DATABASE posts

ENTRYPOINT ["python3", "post_app.py"]
