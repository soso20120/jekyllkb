## JekyllKB v0.1.2


[JekyllKB](http://jekyllkb.com) - A Knowledge Base framework for [jekyll](http://jekyllrb.com) the static site generator in Ruby.

JekyllKB can be used as a knowledge base framework or starter theme for your Jekyll documentation site.

Version 0.1.2 is just a simple Jekyll starter theme. STAY TUNED!

### Installation

1. Install Jekyll: `gem install jekyll`

2. [Fork and clone this repo](https://github.com/AJAlabs/jekyllkb/fork)

3. From your local clone run `bundle install`

4. Once bundler is finished you can fire up Jekyll: `jekyll serve --watch`

That's it! You're now ready to start hacking on your new knowledge base. enjoy!


### Usage

- placeholder


### Resources & Dependancies

- [Bootstrap Sass](http://getbootstrap.com) - [(source)](https://github.com/twbs/bootstrap-sass)
- [Font Awesome Icons](http://fortawesome.github.io/Font-Awesome/icons/) - [(source)](https://github.com/FortAwesome/Font-Awesome)
- [Jekyll](http://jekyllrb.com/) - [(source)](https://github.com/jekyll/jekyll)
- [jekyll-assets](https://github.com/ixti/jekyll-assets)
- [Liquid - Template engine](https://github.com/Shopify/liquid/wiki/Liquid-for-Designers)
- [Sass - Syntactically Awesome Stylesheets](http://sass-lang.com/)

[Introduction to Jekyll-Assets](http://ixti.net/software/2012/12/30/unleash-mr-hyde-introduction-of-jekyll-assets.html)


### Requirements

Installing JekyllKB is easy and straight-forward, but there are a few requirements you’ll need to make sure your system has before you start. [Git](http://git-scm.com) or [rsync](https://developer.apple.com/library/mac/documentation/Darwin/Reference/ManPages/man1/rsync.1.html) is recommended but not required.

- [Ruby](http://www.ruby-lang.org/en/downloads/)
- [RubyGems](http://rubygems.org/pages/download)


### Directory Structure and Ruby on Rails style asset pipeline

```
jekyllkb/
├── _assets/
|    ├── fonts/
|    ├── images/
|    ├── javascripts/
|    |   ├── custom/       // Custom javascripts
|    |   ├── bootstrap.js  // Bootstrap compiled javascript
|    |   ├── jekyllkb.js   // JekyllKB javascript that requires all other javascripts
|    |   ├── jquery.js     // jQuery
|    ├── stylesheets/      // Preprocessed Sass styles
├── _includes/
|    ├── custom/           // directory to store your custom includes
|    ├── analytics.html    // Google Analytics
|    ├── footer.html       //site footer
|    ├── header.html       //site head
├── _layouts/
|    ├── custom/           // directory to store your custom layouts
|    ├── home.html         // homepage layout
|    ├── page.html         // page layout
|    ├── post-index.html   // post listing layout
|    └── post.html         // post layout
├── _plugins/
├── about/
|    ├── index.html        // Default About Page
├── contact/
|    ├── index.html        // Default Contact Page
├── blog/
|    ├── _posts/           // Blog posts directory
|    ├── index.html        // Blog index file
├── kb/
|    ├── _posts/           // Knowledge Base articles directory
|    ├── index.html        // Knowledge Base index file
└── index.html             // Homepage
```


### Customizing 

- placeholder


### Bugs and Feature Requests

Have a bug or a feature request? [Please open a new issue](https://github.com/Synculus/jekyllkb/issues/new). Before opening an issue, please search for existing [issues](https://github.com/Synculus/jekyllkb/issues) in this repo as well as the [mojombo/jekyll](https://github.com/mojombo/jekyll/issues) repository.


### Versioning

Jekyll**KB** is maintained under the Semantic Versioning guidelines as much as possible.

Releases will be numbered with the following format:

`<major>.<minor>.<patch>`

And constructed with the following guidelines:

* Breaking backward compatibility bumps the major (and resets the minor and patch)
* New additions without breaking backward compatibility bumps the minor (and resets the patch)
* Bug fixes and misc changes bumps the patch

For more information on SemVer, please visit [http://semver.org/](http://semver.org/).


### Support, Troubleshooting and Discussions

If you're having any problems with JekyllKB, here are a few resources for finding answeres:
* Official [Jekyll](http://jekyllrb.com) site 
* [JekyllKB](http://jekyllkb.com) repo
* [Jekyll Help repo](https://github.com/jekyll/jekyll-help)
* [stackoverflow](http://stackoverflow.com/questions/tagged/jekyll)
* You can also see if there's someone available at the #jekyllkb or the #jekyll IRC channels on irc.freenode.net


### License

See the [LICENSE](https://github.com//Synculus/jekyllkb/blob/master/LICENSE.md) file for licensing and copyright details.


### Authors

**AJ Acevedo**

- [http://twitter.com/aj_acevedo](https://twitter.com/aj_acevedo)
- [http://github.com/AJ-Acevedo](https://github.com/AJ-Acevedo)
- [http://AJAcevedo.com](http://AJAcevedo.com)
- IRC freenode.net nick: _AJ

**Mike Barnard**

- [http://twitter.com/mbarnard](https://twitter.com/mbarnard)
- [http://github.com/barnardm](https://github.com/barnardm)
- [http://mBarnard.com](http://mbarnard.com)
- IRC freenode.net nick: mbarnard
