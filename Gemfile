source 'https://rubygems.org'

gem 'volt'


# The following gem's are optional for themeing

# Twitter bootstrap
gem 'volt-bootstrap'

# use the bootflat bootstrap theme
gem 'volt-bootflat'

gem 'volt-fields'

gem 'volt-google-maps'#, path: '/Users/ryanstout/Sites/volt/apps/volt-google-maps'


# Server for MRI
platform :mri do
  gem 'thin', '~> 1.6.0'
  gem 'bson_ext', '~> 1.9.0'
end

# Server for jruby
platform :jruby do
  gem 'jubilee'
end

#---------------------
# Needed at the moment
gem 'volt-sockjs', require: false, platforms: :mri