source "https://rubygems.org"

gem "jekyll", "~> 4.3.0" # Replace with your desired Jekyll version
gem "webrick", "~> 1.8" # Required for Jekyll serve in Ruby 3.0+

  group :jekyll_plugins do
    gem "jekyll-feed", "~> 0.12"
    gem "jekyll-seo-tag", "~> 2.7"
    gem "jekyll-gist", "~> 1.5"
    gem "jekyll-paginate", "~> 1.1"
    gem 'jekyll-sitemap'
    gem 'jekyll-redirect-from'
    gem 'jemoji'
    gem 'faraday-retry', '~> 1.0'
  end

  group :development do
    gem "wdm", "~> 0.1.1" if Gem.win_platform?
  end

  group :test do
    gem "html-proofer", "~> 3.18"
  end