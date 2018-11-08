desc 'outputs hello to the terminal'
task :hello do
  puts "hello from Rake!"
end

desc 'outputs hola to the terminal'
task :hola do
  puts "hola de Rake!"
end
rake greeting:hello
hello from Rake!
 
rake greeting:hola
hola de Rake!

namespace :db do
  desc 'migrate changes to your database'
  task :migrate => :environment do
    Student.create_table
  end
end
task :environment do
  require_relative './config/environment'
end