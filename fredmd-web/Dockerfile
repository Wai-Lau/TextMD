# specify the node base image with your desired version node:<version>
#FROM node:6
# replace this with your application's default port
#EXPOSE 8888

FROM fredmd-web
WORKDIR /fredmd/fredmd-web
CMD cd /fredmd/fredmd-web/TextMD/fredmd-web && yarn install && yarn start

