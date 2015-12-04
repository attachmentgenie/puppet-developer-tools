# encoding: utf-8

require 'rubygems'
require 'bundler'
begin
  Bundler.setup(:default, :development)
rescue Bundler::BundlerError => e
  $stderr.puts e.message
  $stderr.puts "Run `bundle install` to install missing gems"
  exit e.status_code
end
require 'rake'

require 'jeweler'
Jeweler::Tasks.new do |gem|
  # gem is a Gem::Specification... see http://docs.rubygems.org/read/chapter/20 for more options
  gem.name = "puppet-developer-tools"
  gem.homepage = "http://github.com/attachmentgenie/puppet-developer-tools"
  gem.license = "MIT"
  gem.summary = %Q{Meta Package for the Puppet Developer Toolchain}
  gem.description = %Q{Meta Package for the Puppet developer setup}
  gem.email = "bram@attachmentgenie.com"
  gem.authors = ["bram vogelaar"]
  # dependencies defined in Gemfile
end
Jeweler::RubygemsDotOrgTasks.new

task :default => :install