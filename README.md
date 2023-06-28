# DevenWordpress
Deze docker container bevat onderstaande elementen:
 - Mysql
 - Phpmyadmin
 - Wordpress

 ## Hoe gebruiken ?
 Kopieer het voorbeeld bestand .sample.env naar .env en pas .env aan naar je eigen parameters, wanneer klaar bewaar het bestand.

 Open nu een nieuw terminal venster en compileer de code (docker-compose up -d), dit commando zal de omgeving compileren met je eigen parameters.

# FS_DIRECT
Om plugins te installeren zal je onderstaande regel moeten manueel toevoegen aan je wp-config.php bestand, dan zal je zonder problemen de plugins kunnen installeren.

`define('FS_METHOD','direct);`