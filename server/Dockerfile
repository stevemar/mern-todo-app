FROM node:8-alpine
RUN mkdir -p /app/todo-server
WORKDIR /app/todo-server
COPY . /app/todo-server
RUN npm install
CMD ["npm", "run" "dev"]
