# dokku-qpdf
A naive hack to get qpdf into a dokku deployment

# Installation
> dokku plugin:install https://github.com/wallyfoo/dokku-qpdf.git qpdf

All future deployments on this server will have qpdf installed.

There's probably a better way, and in truth, if I could get a passthrough to the system /usr/bin, this wouldn't be necessary. But I suspect I'm barking up the wrong tree, and this hack will be good enough.
