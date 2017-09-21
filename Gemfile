source 'https://rubygems.org'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read) rescue ">0"

group :jekyll_plugins do
  gem 'github-pages', versions['github-pages']
  gem 'jekyll-octicons'
  gem 'jekyll-livereload'
  gem 'jekyll-readme-index'
  gem 'jemoji'
end

group :scripts do
  gem 'octokit'
end

group :test do
  gem 'html-proofer'
end

gem 'rb-fsevent', '0.9.8' # See issue https://github.com/guard/listen/issues/431
