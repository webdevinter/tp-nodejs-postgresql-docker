# Utilisation de l'image officielle Node.js
FROM node:16

# Définition du répertoire de travail
WORKDIR /usr/src/app

# Copier les fichiers de l'application
COPY package*.json ./
RUN npm install
COPY . .

# Exposer le port de l'application
EXPOSE 3000

# Commande pour démarrer le serveur
CMD ["node", "server.js"]
