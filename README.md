# nginx
to install
sudo apt install nginx

.............................install database..........................

sudo apt install mysql-server-5.7

after this follow mysql_secure file to set password

...................install php.........................................

sudo apt-get install php-fpm php-mysql

.......................................................................

copy the default page content and pest  /etc/nginx/sites-available/default here

replace the default content

.......................................................................

test nginx -t if fail try sudo nginx -t

if both are failed then there is any broken packeg remove all and try fresh or check nginx default page again 

......................................................................

systemctl reload nginx

.......................................................................

and try 127.0.0.1 or localhost in your browser

......................................................................

to host multiple site with dns follow  create_multiple_host file
for ssl in server with cerbot  create_ssl
https in local with open ssl follow  test.conf (with ssl)

.......................................................................

to install phmyadmin

sudo apt-get install phpmyadmin

to link with tour server 

sudo ln -s /usr/share/phpmyadmin /var/www/folder_name

[now we have a symbolic link in our folder and we can rename it and use after /[folder_name] to access phpmyadmin]

restert  php
systemctl restert php7.2-fpm [in linux it may not effect  it will show Unknown operation restert ]
