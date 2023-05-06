FROM ruby:latest

WORKDIR /application

COPY . /application

CMD ["ruby", "Lab_1_number_6.rb"]