require "bundler/gem_tasks"

desc 'Say Hello'
task :hello do
  puts "Hello there. This is the 'hello' task."
end

desc 'Run tests'
task :default => :test do
  sh 'ruby ./test/todolist_project_test.rb'
end
