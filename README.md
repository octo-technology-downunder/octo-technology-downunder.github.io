# Ocacoz

This website list the training done by Octoz.

### Jekyll

The site built with [Jekyll], a static site generator in [Ruby].

#### Requirements

* [Ruby](https://www.ruby-lang.org/en/downloads/). You can use a virtual enviromement like [RVM](https://rvm.io/) or [RbEnv](https://github.com/rbenv/rbenv).
 * [bundle](http://bundler.io/). The command is : `gem install bundle`
 * [Configure your AWS CLI](http://docs.aws.amazon.com/cli/latest/userguide/cli-chap-getting-started.html) (for deployment only)

#### Commands

* `bundle install` to install the dependencies
* `bundle exec jekyll serve` to run the developement server
* `bundle exec jekyll build` to generate the site in the folder `_site`
* `bundle update` to update the dependencies and the file `Gemfile.lock`
* `pip install --upgrade --user awscli` to install the [AWS CLI](http://docs.aws.amazon.com/cli/latest/userguide/installing.html) (deployment only)
* `aws s3 sync . s3://ocac` to update the site in S3 (deployment only)


[Jekyll]: http://jekyllrb.com/
[Ruby]: https://www.ruby-lang.org
