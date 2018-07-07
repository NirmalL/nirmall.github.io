## Install and build
- Install Jekyll
- Install plugins mentioned in _config.yml
- Run with `jekyll serve --livereload`
- Or run with `jekyll build`

## Old `Gemfile` code (not relevant now)

```
source 'https://rubygems.org'
gem 'github-pages', group: :jekyll_plugins
```

## Image Magick for thumbnailing

Plugin taken from `https://github.com/mrdanadams/jekyll-thumbnailer`

```brew install imagemagick```

Or, if it doesn't work,


```sh
# uninstall 
brew uninstall imagemagick graphicsmagick libpng jpeg
brew cleanup -s

# install
brew install graphicsmagick
```