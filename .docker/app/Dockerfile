FROM ruby:3.2.2-slim

RUN apt-get update -qq

ENV APP_ROOT /app
WORKDIR $APP_ROOT

COPY Gemfile Gemfile.lock $APP_ROOT/
RUN bundle install