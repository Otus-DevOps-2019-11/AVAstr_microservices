FROM ruby:2.2

RUN apt-get update && apt-get install -y build-essential

ENV APP_HOME /app
# RUN mkdir $APP_HOME
COPY . /app

WORKDIR $APP_HOME
RUN bundle install
ENV DATABASE_URL mongodb://mongo
EXPOSE 9292

CMD ["puma"]


#FROM ubuntu:16.04
#
#RUN apt-get update
#RUN apt-get install -y mongodb-server ruby-full ruby-dev build-essential git
#RUN gem install bundler
#RUN git clone -b monolith https://github.com/express42/reddit.git
#
#RUN cd /reddit && bundle install
#COPY mongod.conf /etc/mongod.conf
#COPY db_config /reddit/db_config
#COPY start.sh /start.sh
#
#RUN chmod 0777 /start.sh
#
#CMD ["/start.sh"]
