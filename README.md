# Google Sitemaps Module

[![Build Status](https://secure.travis-ci.org/silverstripe-labs/silverstripe-googlesitemaps.png?branch=master)](http://travis-ci.org/silverstripe-labs/silverstripe-googlesitemaps)

## Maintainer Contact

* Will Rossiter (Nickname: wrossiter, willr) <will@fullscreen.io>

## Requirements

Silverstripe 3.2.x

## Documentation

SilverStripe provides support for the Google Sitemaps XML system, enabling 
Google and other search engines to see all urls on your site. This helps 
your SilverStripe website rank well in search engines, and to encourage the 
information on your site to be discovered by Google quickly.

Therefore, all Silverstripe websites contain a special controller which can 
be visited: http://yoursite.com/sitemap.xml

Flush this route to ensure the changes take effect with: http://yoursite.com/sitemap.xml?flush=1

See http://en.wikipedia.org/wiki/Sitemaps for info on this format.

## Usage Overview

See docs/en for more information about configuring the module.
	
### Notice
This repository uses the git flow paradigm.
After each release cycle, do not forget to push tags, master and develop to the remote origin
```
git push --tags
git push origin develop
git push origin master
```