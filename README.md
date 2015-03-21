# new.gatorlug.org

Currently a prototype of what <http://gatorlug.org> *could* be.

## Plan

Currently I'm trying to look for something that looks *good*. Design ideas would 
be greatly appreciated at this point.

Once we have something that looks decent, I'll clean up the code, perform minor 
design tweaks, fix bugs, and provide polyfills.

When we're happy with the design and code, we'll use 
[`jekyll-import`](http://import.jekyllrb.com/) to import the old site content, 
and switch over the DNS.

## Development

```
$ sudo gem install bundler
$ bundle install
$ bundle exec jekyll serve
```

which should give you some output including a couple lines like:

```
    Server address: http://0.0.0.0:4000/
  Server running... press ctrl-c to stop.
```
