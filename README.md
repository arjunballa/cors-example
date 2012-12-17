Add host entries in /etc/hosts file
127.0.0.1       api.me
127.0.0.1       web.me

Start the api nginx server
sudo ./nginx-api-server/nginx

Start the web nginx server
sudo ./nginx-web-server/nginx

Install Firefox browser and Firebug plugin

Access http://web.me:9991/main.html in Firefox


To Stop api nginx server
sudo ./nginx-api-server/nginx -s stop

To Stop web nginx server
sudo ./nginx-web-server/nginx -s stop
