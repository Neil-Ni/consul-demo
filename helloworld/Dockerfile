FROM google/nodejs

WORKDIR /helloworld
ADD package.json /helloworld/
RUN npm install
ADD . /helloworld

CMD ["node", "app.js"]
