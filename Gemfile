# frozen_string_literal: true

source "https://rubygems.org"

gemspec

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

gem 'wdm', '>= 0.1.0' if Gem.win_platform?

