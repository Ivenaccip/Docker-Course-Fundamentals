FROM python:3.12-alpine3.17

WORKDIR /app

COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt

COPY . .

CMD [ "python", "-m", "flask", "run", "--host=0.0.0.0" ]

#Estamos creando una imagen de Python que tiene hospedada la API para volverse un contenedor