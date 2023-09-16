Configuration Eclipse Mosquitto in Drocker

Start image: docker compose up -d

Access image: docker exec -it mosquitto sh

Command to create login and password: mosquitto_passwd -c /mosquitto/config/mosquitto.passwd **login-name**

Access this mosquitto:

Login: root

Passowrd: 123456

