FROM node
WORKDIR /opt/back
COPY . .
RUN npm install
RUN npm audit fix --force

EXPOSE 3000
ENTRYPOINT ["npm", "start"]