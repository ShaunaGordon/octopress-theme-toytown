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

# Licensing

I'm releasing this under the <abbr title="Don't Be A Dick">DBAD</abbr> License. For the original and translations, check out [Phil Sturgeon's license repo](https://github.com/philsturgeon/dbad).

## DON'T BE A DICK PUBLIC LICENSE

> Version 1, December 2009

> Copyright (C) 2009 Philip Sturgeon <email@philsturgeon.co.uk>
 
 Everyone is permitted to copy and distribute verbatim or modified
 copies of this license document, and changing it is allowed as long
 as the name is changed.

> DON'T BE A DICK PUBLIC LICENSE
> TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION

 1. Do whatever you like with the original work, just don't be a dick.

     Being a dick includes - but is not limited to - the following instances:

   1a. Outright copyright infringement - Don't just copy this and change the name.  
	 1b. Selling the unmodified original with no work done what-so-ever, that's REALLY being a dick.  
	 1c. Modifying the original work to contain hidden harmful content. That would make you a PROPER dick.  

 2. If you become rich through modifications, related works/services, or supporting the original work,
 share the love. Only a dick would make loads off this work and not buy the original works 
 creator(s) a pint.
 
 3. Code is provided with no warranty. Using somebody else's code and bitching when it goes wrong makes 
 you a DONKEY dick. Fix the problem yourself. A non-dick would submit the fix back.
