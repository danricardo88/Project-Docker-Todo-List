FROM node:14
EXPOSE 3000
ADD node_modules.tar.gz /todo-app/front-end
COPY . /todo-app/front-end
WORKDIR /todo-app/front-end
CMD ["npm", "start"]
