## Build website locally on Windows

### 1. Preparation (just once)
* Install Ruby using the RubyInstaller for Windows, see instructions at:

    https://jekyllrb.com/docs/installation/windows/

* Install Jekyll and Bundler gems by running the following command in your terminal:
    ```
    gem install jekyll bundler
    ```
* Navigate to the root directory of your Jekyll site

* Create a 'Gemfile' in your project directory with the following content:

    ```ruby
    source "https://rubygems.org"
    gem 'jekyll', '~> 4.4'
    ````

### 2. Building the site

* Navigate to the root directory of your Jekyll site, if you are not already there.

* Run the following command to build the site:

    ```
    bundle exec jekyll serve
    ```

* Open this address in your browser to see the Jekyll site running locally: ```http://localhost:4000/```