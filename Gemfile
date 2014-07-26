source 'https://rubygems.org'

# Use Berkshelf for resolving cookbook dependencies
gem 'berkshelf', '~> 3.0'

# Install omnibus software
gem 'omnibus-software', :github => 'opscode/omnibus-software',
  :branch => 'master'

gem 'omnibus', :github => 'opscode/omnibus-ruby',
  :branch => 'master'

# Use Chef's software definitions. It is recommended that you write your own
# software definitions, but you can clone/fork Chef's to get you started.
# gem 'omnibus-software', github: 'opscode/omnibus-software'

# Use Test Kitchen with Vagrant for converging the build environment
gem 'test-kitchen',    '~> 1.2'
gem 'kitchen-vagrant', '~> 0.14'
