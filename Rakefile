# Rakefile
begin
  require 'jeweler'
  Jeweler::Tasks.new do |gemspec|
    gemspec.name = "setup_once_context"
    gemspec.summary = "Improve test performance by executing setups only once."
    gemspec.description = "Make your shoulda contexts faster by combining the 'should' blocks (e.g. setup is called only once)."
    gemspec.email = "jpfuentes2@gmail.com"
    gemspec.homepage = "http://github.com/jpfuentes2/setup_once_context"
    gemspec.authors = ["Pratik Naik"]
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler not available. Install it with: sudo gem install jeweler -s http://gemcutter.org"
end

# uniquify.gemspec
Gem::Specification.new do |s|
  s.name        = "setup_once_context"
  s.version     = "1.0.0"
  s.author      = "Pratik Naik"
  s.email       = "jpfuentes2@gmail.com"
  s.homepage    = "http://github.com/jpfuentes2/setup_once_context"
  s.summary = "Improve test performance by executing setups only once."
  s.description = "Make your shoulda contexts faster by combining the 'should' blocks (e.g. setup is called only once)."
  s.files        = Dir["{lib,test}/**/*"] + Dir["[A-Z]*"] + ["init.rb"]
  s.require_path = "lib"
  
  s.rubyforge_project = s.name
  s.required_rubygems_version = ">= 1.3.4"
end
