#!/usr/bin/env bash
# shellcheck disable=SC2154
#configures a new Ubuntu machine nginx
sudo apt-get update
sudo apt-get install nginx -y
sudo ufw allow 'Nginx HTTP'
echo "Holberton School" | sudo tee /var/www/html/index.nginx-debian.html
new_string="listen 80 default_server;\\n\\tlocation \/redirect_me {\\n\\t\\treturn 301 https:\/\/www.youtube.com\/;\\n\\t}"
sudo sed -i "s/listen 80 default_server;/$new_string/" /etc/nginx/sites-enabled/default
echo "Ceci n'est pas une page" | sudo tee /usr/share/nginx/html/404.html
new_string="listen 80 default_server;\\nerror_page 404 \/404.html;\\n\\tlocation = \/404.html {\\n\\t\\troot \/usr\/share\/nginx\/html;\\n\\t\\tinternal;\\n\\t}"
sudo sed -i "s/listen 80 default_server;/$new_string/" /etc/nginx/sites-enabled/default
new_string2="http {\\n\\tadd_header X-Served-By \"$HOSTNAME\";"
sudo sed -i "s/http {/$new_string2/" /etc/nginx/nginx.conf
sudo service nginx start
