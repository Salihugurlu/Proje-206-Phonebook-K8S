# FROM python:alpine
# WORKDIR /search
# COPY requirements.txt requirements.txt
# RUN pip install --upgrade pip
# RUN pip install -r requirements.txt
# EXPOSE 80
# COPY . .
# CMD python ./app.py




FROM python:alpine
COPY . /web-server
WORKDIR /web-server
RUN pip install --upgrade pip
RUN pip install -r requirements.txt
EXPOSE 80
CMD python ./app.py



# FROM python:alpine
# COPY . /app
# COPY requirements.txt requirements.txt
# COPY . .
# WORKDIR /app
# RUN pip install -r requirements.txt
# EXPOSE 80
# CMD python ./app.py

# FROM python:alpine
# RUN apk update && apk add
# EXPOSE 80 
# WORKDIR /web-server
# COPY . .
# RUN pip install -r requirements.txt
# CMD python3 ./app.py