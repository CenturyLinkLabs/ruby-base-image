# Ruby Base Image

A Docker file that creates a Debian-based image with that latest, stable Ruby
and RubyGems versions installed (both compiled from source).

This image provides no default CMD or ENTRYPOINT -- it is intended to be used
as the basis for other images requiring Ruby.

Total image size should be around 360MB.
