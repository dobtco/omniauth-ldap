source 'http://rubygems.org'

gemspec

# Temporarily pulling this ref from github since it has the fix to the SASL
# constant typo. When gem owners bump version we can update the gempsec.
gem net-ldap,
  git: 'git@github.com:ruby-ldap/ruby-net-ldap.git',
  ref: '8031bf5df79ec6fb3d7f7d2540f190b08c3c6df9'

group :development, :test do
  gem 'guard'
  gem 'guard-rspec'
  gem 'guard-bundler'
  gem 'growl'
  gem 'rb-fsevent'
end
