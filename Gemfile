source 'https://rubygems.org'

gemspec

group :development do
  gem 'vagrant',          github: 'mitchellh/vagrant', tag: 'v1.4.3'
  gem 'vagrant-cachier',  github: 'fgrehm/vagrant-cachier'
  gem 'vagrant-pristine', github: 'fgrehm/vagrant-pristine'
  gem 'vagrant-omnibus'
  gem 'guard'
  gem 'guard-rspec'
  gem 'rb-inotify'
end


group :development, :test do
  gem 'rake'
  gem 'vagrant-spec', github: 'mitchellh/vagrant-spec'
  gem 'rspec'
  gem 'coveralls', require: false
end
