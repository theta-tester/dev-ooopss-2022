### Create a ROLE to install http packge and start httpd service; enable service; create a /var/www/htnl/index.html. To create index.html page use ansible template module. The content in index.html should be look like below. Create a variable 'image_url" and pass the image url which u want. Whenever I change url in index.html my httpd service need to restart

    <html>
    <image href= {{ image_url }}.
    </html>
