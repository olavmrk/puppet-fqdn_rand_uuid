source 'https://rubygems.org'

group :development, :unit_tests do
  gem 'metadata-json-lint', :require => false
  gem 'puppetlabs_spec_helper', :require => false
  gem 'puppet-blacksmith', :require => false
  gem 'rspec-puppet', :require => false
  gem 'json_pure', '<= 2.0.1', :require => false if RUBY_VERSION.split('.')[0] == '1'
end

if ENV['PUPPET_GEM_VERSION']
  gem 'puppet', ENV['PUPPET_GEM_VERSION'], :require => false
else
  gem 'puppet', :require => false
end
