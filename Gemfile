#!ruby
source 'https://rubygems.org'

group :development, :test do
  gem 'metadata-json-lint', '2.4.0'
  gem 'puppetlabs_spec_helper', '2.15.0'
  gem 'rake', '13.0.1'
  gem 'rspec', '3.9.0'
  gem 'rubocop', '0.85.1'
end

if puppetversion = ENV['PUPPET_GEM_VERSION']
  gem 'puppet', puppetversion, require: false
else
  gem 'puppet', require: false
end
