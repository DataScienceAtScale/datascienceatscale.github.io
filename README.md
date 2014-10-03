Front Page
==========

[Data Science at Scale Team Front Page](http://datascienceatscale.github.io)

# To create the page #

1. Install node.js and npm
2. `npm install` from the datascienceatscale.github.io directory (*please don't commit these files*)
3. Edit *index.jade* to change the landing page
4. `make` to regenerate the static html
5. `git commit -a` and `git push origin master`

### npm may require setting and unsetting the proxy when being used in and out of LANL network. ###

`npm config set proxy http://proxyout.lanl.gov:8080`
`npm config set https-proxy http://proxyout.lanl.gov:8080`

`npm config rm proxy`
`npm config rm https-proxy`

> npm also obeys `http_proxy` and `https_proxy` environment variables if the npm config is not set.
