# Usa una immagine di base ufficiale di Node.js
FROM node:18

# Imposta la directory di lavoro nel container
WORKDIR /usr/src/app

# Copia il package.json e installa le dipendenze
COPY package*.json ./
RUN npm install

# Copia tutto il codice nel container
COPY . .

# Espone la porta su cui l'app verrà eseguita
EXPOSE 8080

# Comando per avviare l'app
CMD ["npm", "start"]
