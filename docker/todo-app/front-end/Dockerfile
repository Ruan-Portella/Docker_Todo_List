FROM node:16
WORKDIR /app/front-end
EXPOSE 3000
ADD node_modules.tar.gz .
COPY . .
ENTRYPOINT [ "npm" ]
CMD [ "start" ]