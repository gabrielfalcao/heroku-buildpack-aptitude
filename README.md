# chroot + aptitude heroku buildpack

Heroku dynos run Ubuntu installations, this buildpack is based in the
amazing [fakesu](https://github.com/fabiokung/heroku-buildpack-fakesu)
buildpack by @fabiokung.

You can use the multipack heroku buildpack and combine this buildpack
with your own buildpacks, the difference is that you will have the
`sudo` command available so you can install arbitrary `*.deb` packages
that suit your needs.
