source "https://rubygems.org"

group :integration do
  gem "test-kitchen"
  gem "kitchen-vagrant"
  gem "librarian-chef"
end


local_gemfile = File.join(File.dirname(__FILE__), "Gemfile.lw1")
if File.exists?(local_gemfile)
  puts "Loading Gemfile ..." if $DEBUG # `ruby -d` or `bundle -v`
  instance_eval File.read(local_gemfile)
end
