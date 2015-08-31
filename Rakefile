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
  gem.name = 'optipng-r'
  gem.homepage = 'https://github.com/Artie18/optipng'
  gem.license = 'MIT'
  gem.summary = "Ruby interface to 'optipng' tool."
  gem.email = 'artyomfedenko@hotmail.com'
  gem.authors = ['Artyom Fedenko']
end
Jeweler::RubygemsDotOrgTasks.new
