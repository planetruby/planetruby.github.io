# Notes

## Blog Recommendations

- [20 Ruby Developers to Follow Online](http://blog.newrelic.com/2014/04/25/ruby-developers-to-follow/)  by Eric Wilinski (New Relic); April 2014


## Adding Git Submodules


~~~
$ git submodule add --name links https://github.com/planetruby/links.git _data/links
~~~

Note: Do NOT forget to commit.


## Updating Git Submodules

~~~
$ cd _data/books        # change to the submodule directory
$ git pull              # update
$ cd ../..              # get back to your project root
$ git commit -am "books submodule updated"
~~~


## Setup & Updates

Use the following configs

- ruby
- rubynews
- rubyweek
- rubylinks
- rubypodcasts
- jekyll   (Note: from Planet Jekyll repo)
- rubygems
- rubybooks
- rubyapps
- rubyevents
- rubyeventseuropecentral
- rubymeta

