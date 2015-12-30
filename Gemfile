source 'https://rubygems.org'

# next four code lines after this 
# comment were copied from jekyllrb site,
# they have a shorter option in case this one gives
# trouble that goes like the next 2 lines of code:
# source 'https://rubygems.org'
# gem 'github-pages'
require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)
gem 'github-pages', versions['github-pages']
