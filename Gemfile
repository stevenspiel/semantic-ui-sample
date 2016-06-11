source 'https://rubygems.org' do
  gem 'rails', '4.2.5.1'
  gem 'pg', '~> 0.15'
  gem 'less-rails'
  gem 'uglifier', '>= 1.3.0'
  gem 'coffee-rails', '~> 4.1.0'
  gem 'jquery-rails'
  gem 'jbuilder', '~> 2.0'
  gem 'sdoc', '~> 0.4.0', group: :doc
  gem 'turbolinks', '~> 5.x'

  gem 'autoprefixer-rails' # needed for less-rails-semantic_ui
  gem 'daemons'
  gem 'delayed_job_active_record'
  gem 'exception_notification' # action performed when exception raised
  gem 'health_check'
  gem 'less-rails-semantic_ui' # CSS library
  gem 'memoist' # Tool for memoize instance methods
  gem 'paper_trail' # logs all changes to database
  gem 'pdf-forms' # fills out pdf form_templates
  gem 'require_all' # simple way to require all files in a dir
  gem 'slack-notifier' # posts to slack
  gem 'therubyracer' # needed for less-rails-semantic_ui

  group :development, :test do
    gem 'awesome_print'
    gem 'better_errors'
    gem 'dotenv-rails'
    gem 'factory_girl_rails'
    gem 'faker'
    gem 'guard-rails', require: false
    gem 'guard-rspec'
    gem 'guard-shell'
    gem 'pry-nav'
    gem 'pry-rails'
    gem 'pry-rescue'
    gem 'pry-stack_explorer'
    gem 'quiet_assets' # removes logging of asset get requests
    gem 'rspec-core'
    gem 'rspec-rails'
    gem 'spork-rails'
    gem 'spring-commands-rspec'
    gem 'spring-watcher-listen'
    gem 'rubocop', require: false
    gem 'shoulda-matchers'
    gem 'yard'
  end

  group :test do
    gem 'rubocop-rspec'
    gem 'simplecov', require: false
    gem 'timecop'
  end

  group :development do
    gem 'spring'
  end
end
