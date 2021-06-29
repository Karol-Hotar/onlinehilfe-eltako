# frozen_string_literal: true

source "https://rubygems.org"


gemspec

group :test do
  gem "html-proofer", "~> 3.18"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo"
  gem "tzinfo-data"
  gem 'jekyll-feed'
  gem 'jekyll-sitemap'
  gem 'jekyll-seo-tag'
  gem 'jemoji'
  gem 'jekyll-readme-index'
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?

gem "webrick", "~> 1.7"

gem "livereload", "~> 1.6"

gem "jekyll"

gem "github-pages"

gem "sprockets", "~> 3.7"