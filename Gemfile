#!ruby
source 'https://rubygems.org'

group :development, :test do
  gem 'metadata-json-lint', '2.2.0'
  gem 'puppetlabs_spec_helper', '2.14.1'
  gem 'rake', '13.0.1'
  gem 'rspec', '3.9.0'
  gem 'rubocop', '0.82.0'
end

if puppetversion = ENV['PUPPET_GEM_VERSION']
  gem 'puppet', puppetversion, require: false
else
  gem 'puppet', require: false
end
