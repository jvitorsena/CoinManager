FROM node:latest

WORKDIR /usr/src/app/frontend

COPY package*.json ./

# RUN npm install --global yarnk
RUN yarn install
# RUN npm install -g npm@8.7.0
# RUN npm install axios
# RUN npm install

RUN mkdir -p node_modules/.cache && chmod -R 777 node_modules/.cache

EXPOSE 3000

# CMD npm run dev
# RUN npm run build
# CMD npm run build ; npm run start
CMD yarn start
# CMD ["npm", "run", "dev"]
# CMD ["npm", "-s", "build"]
# CMD ["npm", "start"]