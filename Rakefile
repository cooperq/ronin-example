# -*- ruby -*-

require 'rubygems'
require 'hoe'
require './tasks/spec.rb'
require './tasks/yard.rb'

Hoe.spec('ronin-example') do
  self.developer('Author', 'author@example.com')
  self.readme_file = 'README.rdoc'
  self.history_file = 'History.rdoc'
  self.remote_rdoc_dir = ''

  self.extra_deps = [
    ['ronin', '>=0.3.0']
  ]

  self.extra_dev_deps = [
    ['rspec', '>=1.2.8'],
    ['yard', '>=0.5.2']
  ]

  self.spec_extras = {:has_rdoc => 'yard'}
end

# vim: syntax=Ruby
