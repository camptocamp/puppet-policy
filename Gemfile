source :rubygems

if ENV.key?('PUPPET_VERSION')
  puppetversion = "= #{ENV['PUPPET_VERSION']}"
else
  puppetversion = ['>= 2.7']
end

gem 'rake'
gem 'puppet-lint'
gem 'rspec-puppet'
gem 'puppet', puppetversion
gem 'puppetlabs_spec_helper', '>= 0.4.0'

gem 'simplecov', '~> 0.7.0'
gem 'coveralls' unless RUBY_VERSION =~ /^1\.8/
