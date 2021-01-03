FROM node:10.21.0

WORKDIR /mydir
COPY . .
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]


#$ docker build -t backend-example .
#$ docker run --rm -p 8000:8000 -v $(pwd)/logs.txt:/mydir/logs.txt backend-example
