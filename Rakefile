# -*- ruby -*-

require 'rubygems'
require 'hoe'
require './tasks/spec.rb'
require './tasks/yard.rb'

Hoe.spec('ronin-example') do
  self.rubyforge_name = 'ronin-example'
  self.developer('Author', 'author@example.com')
  self.remote_rdoc_dir = ''
  self.extra_deps = [['ronin', '>=0.2.3']]
  self.spec_extras = {:has_rdoc => 'yard'}
end

# vim: syntax=Ruby
