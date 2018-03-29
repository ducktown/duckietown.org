
# duckietown.org的中文站点

duckietown.cn  
ducktown.cn

## To publish the website

Just edit and commit. The `master` branch will be published to `duckietown.cn`.


## To preview the website on your computer

Install Jekyll.

sudo gem install jekyll bundler  


Then run:
~~~
make serve

~~~
or
~~~
jekyll build
jekyll serve
~~~

## 其他方式
## Prerequiement to gem install bundler
You first need to uninstall the ruby installed by Ubuntu with something like
~~~
sudo apt-get remove ruby.
~~~

Then reinstall ruby using rbenv and ruby-build according to their docs:
~~~
cd $HOME  
sudo apt-get update   
sudo apt-get install git-core curl zlib1g-dev build-essential libssl-dev libreadline-dev libyaml-dev libsqlite3-dev sqlite3 libxml2-dev  libxslt1-dev libcurl4-openssl-dev python-software-properties libffi-dev  

git clone https://github.com/rbenv/rbenv.git ~/.rbenv  
echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bashrc  
echo 'eval "$(rbenv init -)"' >> ~/.bashrc  
exec $SHELL  

git clone https://github.com/rbenv/ruby-build.git ~/.rbenv/plugins/ruby-build  
echo 'export PATH="$HOME/.rbenv/plugins/ruby-build/bin:$PATH"' >> ~/.bashrc  
exec $SHELL  

##### rbenv install 2.3.1  
##### rbenv global 2.3.1  

sudo apt-get install ruby  
sudo apt-get install ruby-dev   
ruby -v  
~~~

The last step is to install Bundler:
~~~
sudo gem install bundler  
rbenv rehash
~~~
Then enjoy!

## Install theme
Ref:https://github.com/daviddarnes/garth#installation

As a GitHub Pages remote theme

1. Add `gem "jekyll-remote-theme"` to your `Gemfile` to add the theme as a dependancy
2. gem install eventmachine -v '1.2.5'  
2. Run the command `bundle install` in the root of project to install the jekyll remote theme gem as a dependancy
3. Add `jekyll-remote-theme` to the list of `plugins` in your `_config.yml` file
4. Add `remote_theme: daviddarnes/garth` to your `_config.yml` file to set the site theme
5. Run `bundle exec jekyll serve` to build and serve your site
6. Done! Use the example [`_config.yml`](https://github.com/daviddarnes/garth/blob/master/_config.yml) file to set site-wide options



### 修改rubygems的source源

$ gem sources --add https://gems.ruby-china.org/ --remove https://rubygems.org/
$ gem sources -l
*** CURRENT SOURCES ***

https://gems.ruby-china.org

####  请确保只有 gems.ruby-china.org

$ gem install rails
如果你使用 Gemfile 和 Bundle (例如：Rails 项目)

你可以用 Bundler 的 Gem 源代码镜像命令。
$ bundle config mirror.https://rubygems.org https://gems.ruby-china.org
这样你不用改你的 Gemfile 的 source。
source 'https://rubygems.org/'
gem 'rails', '4.1.0'
...

修改你的 Gemfile 将 http://rubygems.org 改为 https://gems.ruby-china.org/
