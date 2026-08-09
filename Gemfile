source 'https://rubygems.org'

# GitHub Pages builds this site with its own pinned gem set.
# Keep github-pages here so local builds match what Pages runs.
gem 'github-pages', group: :jekyll_plugins

# Plugins listed in _config.yml. Versions come from github-pages above.
group :jekyll_plugins do
  gem 'jekyll-feed'
  gem 'jekyll-paginate'
  gem 'jekyll-redirect-from'
  gem 'jekyll-sitemap'
end

# Jekyll 3.9.3 expects these in the standard library. Ruby 3.4 dropped them
# from the default gems, so they have to be asked for by name.
gem 'base64'
gem 'bigdecimal'
gem 'csv'
gem 'logger'

# Local and CI only. Not used by the Pages build.
# webrick backs `jekyll serve`; Ruby 3 dropped it from the standard library.
group :development, :test do
  gem 'html-proofer', '~> 5.0'
  gem 'rake'
  gem 'webrick'
end
