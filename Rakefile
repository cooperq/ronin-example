# -*- ruby -*-

require 'rubygems'
require 'hoe'

Hoe.plugin :yard

Hoe.spec('ronin-example') do
  self.developer('Author', 'author@example.com')

  self.rspec_options += ['--colour', '--format', 'specdoc']

  self.yard_title = 'Ronin Example Documentation'
  self.yard_options += ['--protected']
  self.remote_rdoc_dir = ''

  self.extra_deps = [
    ['ronin', '>=0.4.0']
  ]

  self.extra_dev_deps = [
    ['rspec', '>=1.3.0'],
    ['yard', '>=0.5.3'],
    ['yard-dm', '>=0.1.0']
  ]
end

# vim: syntax=Ruby
