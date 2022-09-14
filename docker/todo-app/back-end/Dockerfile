FROM node:14-alpine
EXPOSE 3001
COPY . .
ADD node_modules.tar.gz ./
WORKDIR /todo-app/backend/
CMD ["npm", "start"]
