# Ruby Base Image

[![](https://badge.imagelayers.io/centurylink/ruby-base.svg)](https://imagelayers.io/?images=centurylink/ruby-base:latest 'Get your own badge on imagelayers.io')

Debian-based Docker image containing stable versions of Ruby, RubyGems and
Bundler.

Both Ruby and RubyGems are compiled from source and every effort has been made
to keep the image size as small as possible. Check the tags on the image to see
which versions of Ruby are available.

Can be used as the base container for your Ruby application by referencing this
image in the `FROM` line of your `Dockerfile`:

```
FROM centurylink/ruby-base:2.1.2
```

Also can be used as an interactive Ruby environment by running the image with
a shell:

```
docker run -it centurylink/ruby-base:2.1.2 /bin/bash
```
