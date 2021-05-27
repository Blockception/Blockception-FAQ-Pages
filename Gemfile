source "https://rubygems.org"
gem "jekyll", "~> 3.6"
gem "just-the-docs", "~> 0.3.3"
gem 'jekyll-relative-links'

group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-paginate"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?

# kramdown dependency
gem "kramdown-parser-gfm"
