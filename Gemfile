source 'https://rubygems.org'

gem 'rake'
gem 'rspec'
gem 'rails', '5.2.2'
gem 'database_cleaner'
gem 'timecop'
gem 'rpush-redis', '0.4.1'
gem 'rpush-mongoid', github: 'venriq/rpush-mongoid', branch: 'master' #point to a branch that uses Mongoid 6.x

platform :mri do
  gem 'cane'
  gem 'codeclimate-test-reporter', require: nil
  gem 'simplecov', require: false
  gem 'rubocop', require: false
  gem 'byebug'
end

platform :mri_21, :mri_22 do
  gem 'stackprof'
end

platform :ruby do
  gem 'pg'
  gem 'mysql2'
  gem 'sqlite3'
end

platform :jruby do
  gem 'activerecord-jdbc-adapter', '>= 1.2.6'
  gem 'activerecord-jdbcpostgresql-adapter'
  gem 'activerecord-jdbcmysql-adapter'
  gem 'activerecord-jdbcsqlite3-adapter'
  gem 'activerecord-jdbch2-adapter'
  gem 'jdbc-postgres'
  gem 'jruby-openssl'
end

gemspec
