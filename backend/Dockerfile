FROM node:14.17.0
WORKDIR /angular-crash
COPY . .
RUN npm install -g json-server 
CMD ["json-server"  , "--watch" , "/angular-crash/db.json"  , "--port" , "5000" , "--host" , "0.0.0.0"]