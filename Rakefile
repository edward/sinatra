require 'rubygems'
require 'echoe'

task :default => :test

Echoe.new("sinatra") do |p|
  p.author = "Blake Mizerany"
  p.email = "blake.mizerany@gmail.com"
  p.summary = "Classy web-development dressed in a DSL"
  p.url = "http://www.sinatrarb.com"
  p.docs_host = "sinatrarb.com:/var/www/blakemizerany.com/public/docs/"
  p.dependencies = ["mongrel >=1.0.1", "rack >=0.4.0", "mocha >=0.9.0", "test-spec >=0.9.0", "builder >=2.1.2"]
  p.install_message = "*** Be sure to checkout the site for helpful tips!  sinatrarb.com ***"
  p.include_rakefile = true
end
