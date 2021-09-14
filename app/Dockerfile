FROM node:14-alpine as react-build

# ENV REACT_APP_API_URL "http://localhost:8080/"

WORKDIR /app
COPY . ./
RUN yarn
CMD [ "npm", "start" ]
