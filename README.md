# nginx
to install
sudo apt install nginx
-----------------------install database---------------------------
sudo apt install mysql-server-5.7
after this follow mysql_secure file to set password
------------------install php-------------------------------------
sudo apt-get install php-fpm php-mysql
-----------------------------------------------------------------
copy the default page content and pest  /etc/nginx/sites-available/default here
replace the default content
=====================================================
test nginx -t if fail try sudo nginx -t
if both are failed then there is any broken packeg remove all and try fresh or check nginx default page again  
=====================================================
systemctl reload nginx
=====================================================
and try 127.0.0.1 or localhost in your browser
=====================================================
