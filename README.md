![Trike logo](images/octotrike_logo.png "Octo Trike logo")

# Trike project web site repo
This repo is used by [github pages](https://guides.github.com/features/pages/) to generate the web site for the Trike project.

The URL for the Trike website is defined in the CNAME file, www.octotrike.org, and shown in this github repo description.
The site can also be accessed direct from github pages https://octotrike.github.io .

## Making changes
Changes to the master branch, once commited, will update the Trike web site.

## Viewing changes
If the changes need to be previewed, then jekyll can be installed locally. The jekll bundler
can then be used to browse the site at http://localhost:4000/ .

## Installing jekyll
Instructions to install and use jekyll are at https://jekyllrb.com/docs/ . The following commands
were used on a debian based linux (Trisquel) :

* Install a full Ruby development environment `sudo apt install ruby-full`
* Install Jekyll and bundler gems `sudo gem install jekyll bundler`
* Install eventmachine (if required) `sudo gem install eventmachine -v '1.2.7' --source 'https://rubygems.org/'`
* Change into the directory with this repo `cd <path>/octotrike.github.io`
* Install the gems specified by the Gemfile `bundle install` or alternatively `bundle install --path vendor/bundle`
* Build the site and make it available on a local server `bundle exec jekyll serve`
* Now browse to http://localhost:4000

