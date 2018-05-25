# Dockerfile
FROM python:3-alpine

# install nano:
RUN apk add --no-cache nano

# create an /app directory:
RUN mkdir -vp /app

# copy the application code:
COPY clock.py /app

# set the working directory for subsequent instructions:
WORKDIR /app

# specify the default container command, to be overridden:
CMD python clock.py