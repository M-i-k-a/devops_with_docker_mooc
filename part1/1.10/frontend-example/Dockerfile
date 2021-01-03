FROM node:10.21.0

WORKDIR /mydir

COPY . .
RUN npm install
EXPOSE 5000
CMD ["npm", "start"]

#$ docker build -t frontend-example .
#$ docker run -p 5000:5000 --rm frontend-example