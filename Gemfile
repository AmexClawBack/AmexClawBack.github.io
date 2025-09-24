# frozen_string_literal: true
source "https://rubygems.org"

# Core
gem "jekyll", "~> 4.4"

# Theme (keep if you still rely on any Chirpy bits; otherwise remove this line)
gem "jekyll-theme-chirpy", "~> 7.3", ">= 7.3.1"

# Plugins used in _config.yml
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.17"
  gem "jekyll-seo-tag", "~> 2.8"
end

# CI link checking
gem "html-proofer", "~> 5.0", group: :test

# Windows-specific bits
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.2.0", platforms: [:mingw, :x64_mingw, :mswin]
