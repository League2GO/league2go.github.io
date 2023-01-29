# league2go.github.io

The [League2GO.com](https://league2go.com/) blog at http://blog.league2go.com/en/

Your subs found automatically! Try it free, make your life easier. Easily manage 15 free games with no    obligations or credit cards. Visit https://league2go.com/ to start.

Below are our steps to publish our public blog.
## setup

    // install ruby version manager, so you dont need to sudo install gems
    $> brew install rbenv

    // to install the project's ruby version
    $> rbenv install

    // the ruby npm equivalent
    $> gem install bundler

    // in this repo
    $> bundle install

## generate the html

    // build the site
    $> bundle exec jekyll build

    // serve the site to test locally at http://127.0.0.1:4000
    $> bundle exec jekyll serve

    // to publish the site commit changes and push
    $> ... git commit commands ...
    $> git push


## theme

Type Theme (https://rohanchandra.github.io/type-theme)