source 'https://rubygems.org'

gemspec
gem 'json', github: 'flori/json', branch: 'v1.8'

group :development, :test do
  gem 'rspec', '~> 3.2.0'
  gem 'simplecov', '~> 0.9.2', :require => false
  gem 'coveralls', '~> 0.7.11', :require => false
end

group :documentation do
  gem 'countloc', '~> 0.4.0', :platforms => :mri, :require => false
  gem 'yard', '~> 0.8.7.6', :require => false
  gem 'inch', '~> 0.5.10', :platforms => :mri, :require => false
  gem 'redcarpet', '~> 3.2.2', platforms: :mri # understands github markdown
end
