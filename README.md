# CRUD-Python-React-MongoDB

Instalamos 3 paquetes que necesitamos
flask, driver Mongo y un modulo para evitar problemas con el servidor de react

pip install flask Flask-PyMongo flask-cors


mongodb se inicia en el puerto 27017
mongod --port 27017 --dbpath C:\MongoDB\data\db

Descargar desde http://www.mongodb.org/downloads
Instalar .msi archivo en la carpeta C:\mongodb
Cree datos , datos\db , log directorios y mongo.config archivo bajo C:\mongodb .
Agregue las siguientes líneas en el archivo " mongo.config "

port=27017
dbpath=C:\mongodb\data\db\
logpath=C:\mongodb\log\mongo.log
Iniciar servidor:

mongod.exe --config="C:\mongodb\mongo.config"
Conéctese al servidor localhost MongoDB a través de la línea de comandos

mongo --port 27017
Conéctese al servidor remoto MongoDB a través de la línea de comandos con autenticación.

mongo --username abcd --password abc123 --Host server_ip_or_dns --port 27017

Desde consola
show dbs - muestra las bbdd
use nombrebd conecta a esa bd

show collections - muestra colecciones

db.nombrecoleccion.find() -- muestra los objetos
admite .pretty() - leerse mejor



