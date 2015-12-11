source 'https://rubygems.org'
ruby '2.0.0'

# rack-jekyll fails to install under US_ASCII which is what the Jenkins slaves are
# set to.
# Encoding.default_external=Encoding::UTF_8
# Encoding.default_internal=Encoding::UTF_8

gem 'git'
gem 'typogruby'
gem 'jekyll', "~> 3.0"
gem 'jekyll-paginate'
gem 'jekyll-plantuml'
gem 'jekyll-sitemap'
gem 'kramdown'
# Until https://github.com/adaoraul/rack-jekyll/pull/22 is accepted
gem 'rack-jekyll', :git => 'https://github.com/awood/rack-jekyll'
gem 'nokogiri'
gem 'pygments.rb'
gem 'stringex'
# See https://bugzilla.redhat.com/show_bug.cgi?id=1184179
gem 'rack', "= 1.5.2"
gem 'rack-rewrite'
gem 'thin'

group :development do
  gem 'thor'
  gem 'safe_yaml'
  gem 'rack-livereload'
  gem 'guard-livereload'
  gem 'guard-jekyll-plus'
end

