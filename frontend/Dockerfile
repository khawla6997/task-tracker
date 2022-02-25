FROM node:14.17.0
WORKDIR /angular-crash
COPY . .
RUN npm i
RUN npm i -g @angular/cli@11.2.3
CMD ["ng", "serve", "--host", "0.0.0.0"]
