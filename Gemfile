source "https://rubygems.org"
ruby RUBY_VERSION

gem "jekyll"
gem "github-pages", group: :jekyll_plugins

group :jekyll_plugins do
  gem 'jekyll-multiple-languages-plugin'
end

# this gem provides regeneration support improvements on Windows
gem 'wdm', '>= 0.1.0' if Gem.win_platform?
