source "https://rubygems.org"

gem "nocms-pages", git: 'https://github.com/simplelogica/nocms-pages.git', branch: 'master'
gem "nocms-admin", git: 'https://github.com/simplelogica/nocms-admin.git', branch: 'master'

# Declare your gem's dependencies in pages.gemspec.
# Bundler will treat runtime dependencies like base dependencies, and
# development dependencies will be added by default to the :development group.
gemspec

# Declare any dependencies that are still in development here instead of in
# your gemspec. These might include edge Rails or gems from your path or
# Git. Remember to move these dependencies to your gemspec before releasing
# your gem to rubygems.org.

# To use debugger
# gem 'debugger'


group :development, :test do
  gem 'faker'
  gem 'carrierwave' # For development and testing purposes (Images)
  gem 'debugger'
end

group :test do
  gem 'rspec-rails', '~> 3.0.0.beta'
  gem 'factory_girl'
  gem 'capybara'
  gem 'database_cleaner'
  gem 'poltergeist'
end
