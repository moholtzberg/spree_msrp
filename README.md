SpreeMsrp
=========

Add Manufacturer's Suggested Retail Price (MSRP) data to your products.

**Note**: This extension only adds MSRP to the products table and the admin
interface. It is assumed that you have your own views or Deface
overrides that you'd like to use.

Installation
------------

Add spree_msrp to your Gemfile:

```ruby
gem 'spree_msrp'
```

Bundle your dependencies and run the installation generator:

```shell
bundle
bundle exec rails g spree_msrp:install
```

Testing
-------

First bundle your dependencies, then run `rake`. `rake` will default to building the dummy app if it does not exist, then it will run specs. The dummy app can be regenerated by using `rake test_app`.

```shell
bundle
bundle exec rake
```

When testing your application's integration with this extension you may use its factories.
Simply add this require statement to your `spec_helper`:

```ruby
require 'spree_msrp/factories'
```

Copyright (c) 2014 Colin Mattson, released under the New BSD License