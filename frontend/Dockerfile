FROM node:20-alpine
WORKDIR /app
COPY package.json package-lock.json ./
RUN npm install
COPY . .
ENV NEXT_PUBLIC_RESTFUL_API=http://localhost:8000/api
RUN npm run build
EXPOSE 3000
CMD ["npm", "run", "start"]