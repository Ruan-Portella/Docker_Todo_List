FROM node:16
WORKDIR /app/back-end
EXPOSE 3001
ADD node_modules.tar.gz .
COPY . .
ENTRYPOINT [ "npm" ]
CMD [ "start" ]