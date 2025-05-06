# Utiliser l'image officielle de Nginx
FROM nginx:latest

# Copier les fichiers front-end dans le répertoire de l'image Nginx
COPY softy-pinko-front-end /var/www/html/softy-pinko-front-end

# Copier la configuration de Nginx dans le répertoire approprié
COPY softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf
