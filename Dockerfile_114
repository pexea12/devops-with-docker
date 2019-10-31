FROM ruby:2.6.0

COPY rails-example-project /rails-example-project
WORKDIR /rails-example-project
EXPOSE 3000
RUN bundle install \
  && apt-get update \
  && apt-get install -y nodejs \
  && rails db:migrate
CMD ["rails", "s"]
