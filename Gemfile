source "https://rubygems.org"

# Jekyll
gem "jekyll", ">= 3.8.4"

# Asynchronous HTTP Client (EventMachine + Ruby)
gem "em-http-request"

# Jekyll Env.
group :jekyll_plugins do
  gem "jekyll-algolia" # Algolia Search Ruby Library & Site Search Library
  gem "jekyll-include-cache", :group => :default
  gem "jekyll-sitemap", :group => :default
end

# Production Env.
group :production do
  gem "nokogiri"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0" if Gem.win_platform?
