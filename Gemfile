source 'https://rubygems.org'

gem 'jekyll', '~> 4.3'

group :jekyll_plugins do
  gem 'jekyll-feed'
  gem 'jekyll-gist'
  gem 'jekyll-paginate'
  gem 'jekyll-sitemap'
  gem 'jekyll-redirect-from'
  gem 'jemoji'
end

gem 'webrick', '~> 1.8'

# Windows/JRuby don't ship zoneinfo data by default
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem 'tzinfo', '>= 1', '< 3'
  gem 'tzinfo-data'
end
