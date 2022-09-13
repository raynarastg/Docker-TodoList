FROM mjgargani/puppeteer:trybe1.0
ADD node_modules.tar.gz ./
WORKDIR /todo-app/tests/
RUN npm install
COPY . .
CMD ["npm", "test"]
