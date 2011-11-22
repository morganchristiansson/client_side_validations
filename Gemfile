source "http://rubygems.org"

# Specify your gem's dependencies in client_side_validations.gemspec
gemspec

ruby_minor_version = RUBY_VERSION.split('.')[1].to_i
if ruby_minor_version == 8
  gem 'minitest'
  group :debug do
    gem 'ruby-debug'
  end
elsif ruby_minor_version == 9
  group :debug do
    gem 'ruby-debug19', :require => 'ruby-debug'
  end
end

