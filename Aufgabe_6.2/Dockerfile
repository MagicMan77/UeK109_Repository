# Verwenden Sie das offizielle Nginx-Image als Basis
FROM nginxinc/nginx-unprivileged

# Kopieren Sie die HTML-Datei in den Container
COPY index.html /usr/share/nginx/html/ 

# Setzen Sie den Arbeitsverzeichnis auf das Nginx-Verzeichnis
WORKDIR /usr/share/nginx/html

# Port 80 für den Container freigeben
EXPOSE 80

# Starten Sie den Nginx-Server beim Start des Containers
CMD ["nginx", "-g", "daemon off;"]