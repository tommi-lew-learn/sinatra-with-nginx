FROM ruby:3.1.0-alpine

ADD . /app
WORKDIR /app

RUN apk add --no-cache build-base

RUN gem install bundler:2.3.3

RUN bundle install

EXPOSE 4567

CMD ["bundle", "exec", "ruby", "app.rb", "-o", "0.0.0.0"]
