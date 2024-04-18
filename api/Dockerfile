# Utilisation d'une image Node.js compatible ARM
FROM node:14

# Création du répertoire de travail
WORKDIR /api

# Copie des fichiers package.json et package-lock.json
COPY package*.json ./

# Installation des dépendances
RUN npm install

# Copie du reste du code source
COPY . .

# Exposition du port 3000
EXPOSE 3000

# Commande de démarrage de l'application
CMD ["node", "server.js"]
