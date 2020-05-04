# The Best Motherfucking Website
Source of [The Best Motherfucking Website](https://thebestmotherfucking.website)  
Based on [motherfuckingwebsite](http://motherfuckingwebsite.com/) and [bettermotherfuckingwebsite](http://bettermotherfuckingwebsite.com/)

This is all good, but I want to use this for a simple website now. I dont want to remove junk. I want to start adding content NOW. Thats why I stripped back the less necessary stuff and just kept the nice styling.

## Clone the repo
`git clone https://github.com/denysvitali/thebestmotherfuckingwebsite`

## Deployment instructions
~~See `partial-nginx.conf` for the configuration file~~  
~~## Build instructions~~
~~In order to build this project, you'll need [Yarn]~~

~~Visit http://localhost:8080 and you'll be able to improve / view the website :)~~

What motherfucking programmer wanted to make things complicated. Since when was opening a HTML file in your browser so difficult, motherfuckers.

```
Owner@E7470PC MINGW64 ~/Documents/thebestmotherfuckingwebsite (master)
$ git rm yarn.lock webpack.config.prod.js webpack.config.js tsconfig.json package.json
rm 'package.json'
rm 'tsconfig.json'
rm 'webpack.config.js'
rm 'webpack.config.prod.js'
rm 'yarn.lock'

The motherfucking purge continues
        deleted:    .jshintrc
        deleted:    nginx/README.md
        deleted:    nginx/snippets/cors.conf
        deleted:    nginx/snippets/gzip.conf
        deleted:    nginx/snippets/ssl_best.conf
        deleted:    nginx/thebestmotherfuckingwebsite.conf
        deleted:    src/dist/LICENSE.txt
        deleted:    src/dist/js/jquery-2.2.4.min.js
        deleted:    src/img/cat.jpg
        deleted:    src/img/css3.svg
        deleted:    src/img/html5.svg
        deleted:    src/img/js.svg
        deleted:    src/img/kopimi.svg
        deleted:    src/index.ts
        deleted:    src/js/main.fucking.js
        deleted:    src/less/main.less
        deleted:    src/pug/index.pug
        deleted:    src/pug/tracking.html

```
Who needs this motherfucking stuff, still have to remove the JS, tracking files, fake JQuery, lots of CSS and the NGinx configurations folder.

Until your left with one index.html file not even a need for a motherfucking style sheet. We want this portable. 

## Want something to be changed?
[Open an issue](https://github.com/denysvitali/thebestmotherfuckingwebsite/issues) and let's discuss it. If you want to implement it yourself do it freely and make a PR.
