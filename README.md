# nbdev-jekyll-theme

A Jekyll theme for [nbdev](https://nbdev.fast.ai) based on [documentation-theme-jekyll](https://jekyllthemes.io/theme/documentation).


## Usage

We recommend that you use repo template [nbdev template](https://github.com/fastai/nbdev_template/) to create new nbdev projects.  [nbdev template](https://github.com/fastai/nbdev_template/) containts this theme as well as other supporting files you need to get started.

## Development

The following are instructions for using nbdev-jekyll-theme without the template, which can be useful for testing or development.

### Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "jekyll-remote-theme"
```

And add these lines to your Jekyll site's `_config.yml`:

```yaml
plugins:
    - jekyll-remote-theme
    
remote_theme: fastai/nbdev-jekyll-theme
```

And then execute:

    > bundle install


### Serving

Your theme is setup just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.


### Overriding This Theme

Any site that uses this theme will only use the files in `_layouts`, `_includes`, `_sass` and `assets`.  If you wish to override this theme, you must create the same directory and file in your local project.  For example, to change your site's favicon, you can create a file named `assets/images/favicon.ico` to override the default favicon contained in this theme.

_Note: This theme does not distribute certain files that are bundled with [nbdev template](https://github.com/fastai/nbdev_template) such as sitemap.xml, feed.xml, and various configuration files and notebooks._

## Resources

- [Jekyll Docs](https://jekyllrb.com/docs/)
- [How to create a Jekyll Theme](https://www.siteleaf.com/blog/making-your-first-jekyll-theme-part-2/)
- [nbdev docs](https://nbdev.fast.ai/)
- [nbdev repo template](https://github.com/fastai/nbdev_template)
