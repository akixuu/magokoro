source "https://rubygems.org"

gem 'webrick'

gem "github-pages", group: :jekyll_plugins # to upgrade, run `bundle update github-pages

group :jekyll_plugins do
    gem 'jekyll-sass-converter'
    gem 'jekyll-loading-lazy'
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
gem "tzinfo", ">= 1", "< 3"
gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
