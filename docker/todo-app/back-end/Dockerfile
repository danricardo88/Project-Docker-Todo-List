FROM node:14
EXPOSE 3001
ADD node_modules.tar.gz /toto-app/back-end
COPY . /toto-app/back-end
WORKDIR /toto-app/back-end
CMD ["npm", "start"]