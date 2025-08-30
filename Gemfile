# The source of the gems.
source "https://rubygems.org"

# This is where you manage which Jekyll version is used to run.
# To use a different version, change it below, save the file, and run `bundle install`.
# Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This ensures the proper Jekyll version is running. Happy Jekylling!

# Use the GitHub Pages gem to manage Jekyll and its plugins.
gem "github-pages", group: :jekyll_plugins

# Add gems that are no longer default in Ruby 3.4+
# and are required for Jekyll or its dependencies to run correctly.
gem "csv"
gem "logger"
gem "base64"
gem "bigdecimal"

# If you want to use a specific version of Jekyll, uncomment the line below.
# To upgrade, run `bundle update`.
# gem "jekyll"

# Windows-specific gem for file system monitoring.
gem "wdm", "~> 0.1.0" if Gem.win_platform?

# Jekyll plugins are managed here.
group :jekyll_plugins do
  # gem "jekyll-archives"
  gem "jekyll-feed"
  gem 'jekyll-sitemap'
  gem 'hawkins'
end