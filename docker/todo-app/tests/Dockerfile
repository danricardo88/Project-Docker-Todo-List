FROM mjgargani/puppeteer:trybe1.0
EXPOSE 3000
ADD node_modules.tar.gz /todo-app/test
COPY . /todo-app/test
WORKDIR /todo-app/test
CMD ["npm test"]

