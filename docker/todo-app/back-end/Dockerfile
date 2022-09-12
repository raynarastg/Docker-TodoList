FROM node:14-alpine
EXPOSE 3001
ADD node_modules.tar.gz ./
WORKDIR /todo-app/backend/
COPY . .
CMD ["npm", "start"]
