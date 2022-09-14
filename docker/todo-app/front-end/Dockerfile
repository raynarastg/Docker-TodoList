FROM node:14-alpine
EXPOSE 3000
COPY . .
ADD node_modules.tar.gz ./
WORKDIR /todo-app/frontend/
CMD ["npm", "start"]
