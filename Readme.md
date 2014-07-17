Heroku buildpack: Python and PhantomJS
========================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for Python apps and ship with console application PhantomJS.


Usage
-----

Example usage:

If your project repo have not a remote branch named heroku (in other words, you have not run `heroku create`), in your project directory:

    $ heroku create --buildpack git://github.com/wikty/heroku-buildpack-python-phantomjs.git

If your project repo has a remote branch named heroku, in your project directory:

    $ heroku config:add BUILDPACK_URL=git://github.com/wikty/heroku-buildpack-python-phantomjs.git

*list git repo remote branch: `git remote -v`*

**Thanks** [stomita's phantomjs buildpack](https://github.com/stomita/heroku-buildpack-phantomjs)
