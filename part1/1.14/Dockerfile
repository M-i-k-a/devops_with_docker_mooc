FROM ruby:2.6.0

COPY . /usr/src/rails-example-project
WORKDIR /usr/src/rails-example-project
EXPOSE 3000
RUN apt-get update && apt-get install -y nodejs
RUN bundle install
RUN rails db:migrate
CMD ["rails", "s"]

#$ docker build -t rails-app .
#$ docker run -p 3000:3000 rails-app