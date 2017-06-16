# apache-config

Config pour magimat class-guru:

1. installation apache  (sudo apt-get install apache2 apache2-dev)

     port 80 et 443 doivent être ouverts dans console google compute

2. sudo a2enmod ssl  (ajout module ssl pour pouvoir installer lets encrypt)

3. let's encrypt  (https://letsencrypt.org/getting-started/   https://certbot.eff.org/)

4. ajout conf pour magimat.ca dans /etc/apache2/sites-enabled/  (fichier conf de ce repo)

5. copy login.html dans /var/www/html
