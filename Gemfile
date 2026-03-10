# frozen_string_literal: true
source "https://rubygems.org"

gem "jekyll"
gem "faraday-retry"

# Ruby 3.4+ removed these from default gems; github-pages/jekyll 3.x needs them
gem "csv"
gem "base64"
gem "bigdecimal"
gem "erb"

# Gems loaded irrespective of site configuration.
group :jekyll_plugins do
  gem "github-pages", "~> 232"
  # gem "jekyll-seo-tag", "~> 1.5"
end

group :development do
  gem "webrick"
end
