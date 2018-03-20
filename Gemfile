source 'https://rubygems.org'

gem 'rake', '~> 10.0'
gem 'rack', '~> 1.0'
gem 'rack-test', '~> 0.6'
gem 'activesupport', '~> 4.0'
gem 'rubyzip', '~> 1.0'
gem 'bcrypt', '~> 3.0'
gem 'multi_json', '~> 1.0'
gem 'oj', '~> 2.0'
gem 'libxml-ruby', '~> 2.0'
gem 'rsolr', '~> 1.0'
gem 'minitest', '~> 4.0'
gem 'cube-ruby', require: "cube"
gem 'pony'
gem 'addressable', '= 2.3.5'
gem 'omni_logger'
gem 'thin'
gem 'rubocop', require: false

# Testing
group :test do
	gem 'simplecov'
	gem 'pry'
	gem 'email_spec'
	gem 'test-unit-minitest'
	gem 'minitest-reporters', '>= 0.5.0'
end

# NCBO gems (can be from a local dev path or from rubygems/git)
gem 'goo', git: 'https://github.com/ncbo/goo.git', branch: 'staging'
gem 'sparql-client', git: 'https://github.com/ncbo/sparql-client.git', branch: 'staging'

# ResourceIndex dependencies (managed per-platform)
gem 'ncbo_resource_index', git: 'https://github.com/ncbo/resource_index.git'
