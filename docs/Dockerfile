FROM jekyll/jekyll:3.8.6
COPY Gemfile /srv/jekyll
RUN bundle install
CMD jekyll serve --watch --force_polling --verbose --livereload
