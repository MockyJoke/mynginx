docker run -d -p 443:443 -p 80:80 -v ssl:/ssl -v $(pwd):/etc/nginx/sites-available mynginx
