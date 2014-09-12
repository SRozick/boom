# Inherent Knowledge, LLC #

This is a web development project to market myself as a web developer and SEO.  

As of this iteration, the project is built around [Middleman](http://middlemanapp.com/) project template with the [SASS](http://sass-lang.com/) version of the [ZURB Foundation](http://foundation.zurb.com/) Framework.

## Todo ##
1. Move Middleman setup out to new Readme in Wiki
1. Add Ruby setup to new Readme in Wiki
1. Move git setup out to new Readme in Wiki
1. Move Useful Resources out to page
1. Create links page from here to various notes pages

# Useful Resources #

## Web Design ##
### Typography ###
### CSS Design Elements ###
### Colorography ###

## Frameworks ##
### Foundation ###
### Bootstrap ###

## Code ##
### Ruby ###
### SQL ###
### HTML ###
### Java ###
### JQuery ###
### Javascript ###

## SEO ##

## Social Media ##
### Facebook ###
### Google Plus ###
### LinkedIn ###


## Installation ##

Make sure to have:

1. ruby
1. git

Setup as follows:

1. $ gem install middleman
1. $ bundle update
1. Download and install Node for Mac from nodejs.org
1. Clone zurb-foundation
	a. $ mkdir ~/.middleman
	a. $ cd ~/.middleman
	a. $ git clone git://github.com/axyz/middleman-zurb-foundation.git ~/.middleman/zurb-foundation
1. Create new middleman project
	a. $ middleman init <my_project_directory> --template=zurb-foundation
	a. $ cd <my_project_directory>
	a. $ sudo npm install -g bower
	a. $ bower install
	a. $ bundle update
	a. $ bundle install
	a. $ bundle exec middleman
1. Clean up
	a. $ rm -rf ~/my/project/directory/.git
	a. Browse to github.com and create remote repository
1. Set up git
	a. $ git init
	a. $ git add .
	a. $ git commit -m "Initial commit"
	a. $ git remote add origin git@github.com:<project_name>.git
	a. $ git push origin -u  master
1. Set up git flow
	a. $ git flow init
	a. $ git push origin -u develop
1. Start developing
	a. $ git flow feature start <feature_name>
	a. $ git push origin -u feature/<feature_name>




# Licenses #

## ZURB Foundation License ##

Copyright (c) 2011 ZURB, http://www.zurb.com/

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.