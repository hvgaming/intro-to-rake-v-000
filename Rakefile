
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

namespace :db do
 
  ...
 
  desc 'seed the database with some dummy data'
  task :seed do
    require_relative './db/seeds.rb'
  end
end