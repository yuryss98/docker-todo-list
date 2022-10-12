FROM mjgargani/puppeteer:trybe1.0
WORKDIR /aplication
ADD ./node_modules.tar.gz .
COPY . .
ENTRYPOINT ["npm", "test"]

