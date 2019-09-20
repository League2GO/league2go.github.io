# league2go.github.io

## setup

    // install ruby version manager, so you dont need to sudo install gems
    $> brew install rbenv

    // install a version of ruby (use rbenv install -l to find a newer version)
    $> rbenv install -v 2.5.3

    // set your global ruby version
    $> rbenv global 2.5.3

    // check if you have the proper ruby version
    $> ruby -v
    // expect to see version 2.5.3 (or the version you installed)

    // the ruby npm equivalent
    $> gem install bundler

    // in this repo
    $> bundler install

## generate the html

    // build the site
    $> bundler exec jekyll build

    // serve the site to test locally at http://127.0.0.1:4000
    $> bundler exec jekyll serve

    // to publish the site commit changes and push
    $> ... git commit commands ...
    $> git push


## theme

Type Theme (https://rohanchandra.github.io/type-theme)