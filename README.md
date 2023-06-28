# DevenWordpress
Deze docker container bevat onderstaande elementen:
 - Mysql
 - Phpmyadmin
 - Wordpress

# FS_DIRECT
Om plugins te installeren zal je onderstaande regel moeten manueel toevoegen aan je wp-config.php bestand, dan zal je zonder problemen de plugins kunnen installeren.

`define('FS_METHOD','direct);`