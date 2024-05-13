# Docker MariaDB

Installation d'un serveur MariaDB avec Docker.  
Services complémentaires : PHPMyAdmin

---  

## Installation

1. Dupliquer le fichier .env-sample et le renommer en .env :  
   `cd docker_mariadb`  
   `cp .env-sample .env`  
   Modifier ce fichier en renseignant vos informations

2. Monter les conteneurs Docker :  
   `docker-compose up -d --build`
