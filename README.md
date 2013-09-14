test
====
this
helpers do  
    include Rack::Utils  
    alias_method :h, :escape_html  
end 

then this:
additional 
 
== Installation

1. install javascript runtime (e.g. nodejs):
       sudo apt-get install nodejs

2. install rvm. See {this guide}[link:https://rvm.io/rvm/install/]:
       \curl -L https://get.rvm.io | bash -s stable --autolibs=3 --rails
       rvm install ruby-2.0.0-p0 # optional
       rvm install ruby-1.9.3 
       rvm --default use ruby-1.9.3
       gem install rails
