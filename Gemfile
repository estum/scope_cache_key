source 'https://rubygems.org'

# Specify your gem's dependencies in scope_cache_key.gemspec
gemspec

gem 'rspec', '~> 2.13.0'
gem 'activerecord', '~> 3.2.12'
gem 'actionpack', '~> 3.2.12'
gem 'faker', '~> 1.1.2'
gem 'pry'
gem 'rake'

# With the help of https://github.com/sferik/rails_admin/blob/master/Gemfile
platforms :jruby do
  gem 'activerecord-jdbcpostgresql-adapter', '>= 1.2'
  gem 'jdbc-postgres', '>= 9.2'
end

platforms :ruby, :mswin, :mingw do
  gem 'pg'
end
