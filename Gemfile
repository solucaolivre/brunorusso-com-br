# frozen_string_literal: true

source "https://rubygems.org"

gemspec

group :test do
  gem "html-proofer", "~> 3.18"
end

gem 'racc', '~>1.5.2'
gem 'http_parser.rb', '~> 0.6.0'
gem 'eventmachine'

group :jekyll_plugins do
    gem "jekyll-youtube"
    gem 'jekyll-paginate'
    gem 'jekyll-analytics'
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?
