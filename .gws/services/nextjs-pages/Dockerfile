FROM node:20-alpine
WORKDIR /app
COPY package.json ./
RUN npm install
EXPOSE 3000
ENV HOST=0.0.0.0
CMD ["sh", "-c", "npm install && npx next dev -H 0.0.0.0 -p 3000"]
