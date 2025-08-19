source 'https://rubygems.org'

gem "jekyll", "~> 4.4.1" # installed by `gem jekyll`
# gem "webrick"        # required when using Ruby >= 3 and Jekyll <= 4.2.2

gem "just-the-docs", "0.10.1" # pinned to the current release
# gem "just-the-docs"        # always download the latest release

# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# gem "github-pages", group: :jekyll_plugins
# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
