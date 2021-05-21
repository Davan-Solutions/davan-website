source 'https://rubygems.org'
gem "jekyll"
gem "github-pages"

group :jekyll_plugins do
    gem 'jekyll-feed'
    gem 'jekyll-sitemap'
    gem 'jekyll-paginate'
    gem 'jekyll-seo-tag'
    gem 'jekyll-archives'
    gem 'jekyll-figure'
    gem 'bootstrap', '~> 4.4.1'
    gem 'kramdown'
    gem 'rouge'
end



# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
    gem "tzinfo", "~> 1.2"
    gem "tzinfo-data"
  end
  
  # Performance-booster for watching directories on Windows
gem 'wdm', '>= 0.1.0' if Gem.win_platform?