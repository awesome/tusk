# -*- ruby -*-

require 'rubygems'
require 'hoe'

Hoe.plugins.delete :rubyforge
Hoe.plugin :minitest
Hoe.plugin :gemspec # `gem install hoe-gemspec`
Hoe.plugin :git     # `gem install hoe-git`

Hoe.spec 'tusk' do
  developer('Aaron Patterson', 'aaron@tenderlovemaking.com')
  self.readme_file   = 'README.markdown'
  self.history_file  = 'CHANGELOG.rdoc'
  self.extra_rdoc_files  = FileList['*.{rdoc,markdown}']

  self.extra_dev_deps << ['pg', '~> 0.14.0']
end

# vim: syntax=ruby
