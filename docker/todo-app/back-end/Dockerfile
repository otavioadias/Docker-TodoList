FROM node:14
WORKDIR /todobackend
COPY package*.json ./
RUN npm install
ADD node_modules.tar.gz .
COPY ./ .
EXPOSE 3001
ENTRYPOINT ["npm"]
CMD ["start"]