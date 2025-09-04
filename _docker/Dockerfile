FROM jekyll/builder
WORKDIR /work
RUN chown -R root:root /work && chmod -R 777 /work
COPY Gemfile .
RUN bundle install
WORKDIR /srv/jekyll
