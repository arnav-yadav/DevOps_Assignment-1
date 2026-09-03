FROM node:20
WORKDIR /app
COPY . .
RUN npm install && npm run build
EXPOSE 5173
CMD ["npx", "vite", "--host", "0.0.0.0"]