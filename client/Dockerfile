FROM node:8-alpine
RUN mkdir -p /app/todo-client
WORKDIR /app/todo-client
COPY . /app/todo-client
RUN npm install
CMD ["npm", "run" "start"]
