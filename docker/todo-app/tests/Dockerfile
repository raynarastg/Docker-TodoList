FROM mjgargani/puppeteer:trybe1.0
COPY . .
ADD node_modules.tar.gz ./
WORKDIR /todo-app/tests/
CMD ["npm", "test"]
