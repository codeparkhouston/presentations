## Getting started

The `base` folder contains everything you need to create a [reveal.js](http://lab.hakim.se/reveal-js/) presentation. This has a few advantages over heavy-weight presentation formats like Keynote:

* The slides can be kept in a nice, easy-to-read text file.
* Changesets can be visualized with git.
* They're really (really) easy to put together, and look nice OOTB.

First things first, clone the repo. Now copy the base folder to a new location:

```console
$ cd presentations; cp -R base my-talk
```
Now install the bundle:

```console
$ cd my-talk; bundle install
```

Kick off the middleman server and [check out your handywork](http://localhost:4567):

```console
$ bundle exec middleman server
```

The base presentation uses [Middleman](http://middlemanapp.com/) to keep things neat and tidy. It also uses [haml](http://haml.info), but feel free to just, ya know, not use it if haml gives you the creeps.

