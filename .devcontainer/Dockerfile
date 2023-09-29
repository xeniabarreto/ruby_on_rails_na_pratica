FROM ruby:2.7.8-bullseye

RUN apt-get update && apt-get install git
RUN gem install ruby-lsp -v 0.4.5
RUN gem install rubocop
RUN gem install debug
RUN gem install solargraph
RUN gem install rails -v 5.2.8.1