FROM node:14-alpine
WORKDIR /aplication
EXPOSE 3001
ADD ./node_modules.tar.gz .
COPY . .
ENTRYPOINT ["npm", "start"]

