require "bundler/gem_tasks"
require 'rubygems'

require 'rake'
require 'rake/testtask'

desc "run all tests"
Rake::TestTask.new do |t|
  t.libs << "test"
  t.test_files = FileList['test/*_test.rb']
  t.verbose = true
end
