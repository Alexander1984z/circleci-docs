source 'https://rubygems.org'

ruby '2.5.1'

gem 'jekyll', '4.0.0'
gem 'html-proofer', "3.9.1"
gem 'jekyll-sitemap', '>= 1.3.0'

gem 'jekyll-assets', '>= 3.0.11'
# jekyll-assets depends on sprockets, which depends on rack, which has two
# security vulnerabilities prior to 2.0.6.
# https://nvd.nist.gov/vuln/detail/CVE-2018-16471
# https://nvd.nist.gov/vuln/detail/CVE-2018-16470
gem "rack", ">= 2.0.6"

group :jekyll_plugins do
  gem 'jekyll-algolia', '~> 1.5', '>= 1.5.0'
end
