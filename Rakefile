# -*- ruby -*-

require 'rubygems'
require 'hoe'

Hoe.plugin :git
Hoe.plugin :gemspec
Hoe.plugins.delete :rubyforge

Hoe.spec 'minitest-rails-capybara' do
  developer 'Mike Moore', 'mike@blowmage.com'

  self.summary     = 'Capybara integration for MiniTest and Rails'
  self.description = 'Adds Capybara feature tests in MiniTest and Rails.'
  self.urls        = ['http://blowmage.com/minitest-rails-capybara']

  self.history_file = "CHANGELOG.rdoc"
  self.readme_file  = "README.rdoc"
  self.testlib      = :minitest

  license "MIT"

  dependency 'minitest-rails',    '~> 1.0.0'
  dependency 'capybara',          '~> 2.0'
  dependency 'minitest-capybara', '~> 0.4'
  dependency 'minitest-metadata', '~> 0.4'
end

# vim: syntax=ruby
