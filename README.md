Base project on serve
=============

Learn more about serve:

<https://github.com/jlong/serve/>

How install and run project?
-------------------------------

1. Install ruby

    debian/ubuntu: apt-get install ruby
    windows: http://rubyinstaller.org/downloads/
             Ruby 1.8.7-p370
             DevKit-tdm-32-4.5.2-20111229-1559-sfx.exe
             faq: https://github.com/oneclick/rubyinstaller/wiki/Development-Kit
                 cd C:\DevKit
                 ruby dk.rb init
                 ruby dk.rb install
    os x: already installed

2. Install rubygems

    debian/ubuntu:
        apt-get install rubygems
        export PATH=/var/lib/gems/1.8/bin:$PATH
    windows: http://rubygems.org/pages/download
    os x: already installed

3. Install bundle:

    gem install bundle


4. Install gems:

    bundle install

5. Run serve:

    serve

6. http://localhost:3000