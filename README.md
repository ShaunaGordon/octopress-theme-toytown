# Toytown

Toytown is a responsive theme for Octopress.

It's currently a work in progress, and so, some styles may have been missed. Feel free to report them or create a pull request.

## Install

Type the code below in terminal.

```bash
cd octopress
git clone git://github.com/ShaunaGordon/octopress-theme-toytown.git .themes/toytown
rake install['toytown']
rake generate
```

## Configuration

Toytown comes with a couple of configuration goodies. It can read the configuration file to automatically add an "about me" page, GitHub profile link, and a "highlights" page. 

The GitHub profile page link uses the same config entry as the repository list sidebar widget. The rest require the addition of one or more entries:

```yaml
# About page
about_page: about

# "Highlights" Page
highlights_page: blog/categories/highlights
highlights_text: Highlights
```

In the case of the "Highlights" page, `highlights_text` is optional and will default to "Highlights" if omitted (and, of course, no link will be rendered if `highlights_page` is omitted).