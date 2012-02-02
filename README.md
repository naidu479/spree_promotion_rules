Spree Promotion Rules
=====================

Spree Promotion Rules is a collection of spree promotion rules.  Currently the only rule included is support for Roles.  This allows you to only apply promotions to designated roles.

Installation
------------

Include the gem to your Gemfile

```ruby
# spree 0.70.x
gem 'spree_promotion_rules', :git => 'git://github.com/tavon/spree_promotion_rules', :branch => '0-70-stable'
```

Next install the necessary migrations db:migrate

```bash
rails g spree_promotion_rules:install
rake db:migrate
```

Testing
-------

Be sure to add the rspec-rails gem to your Gemfile and then create a dummy test app for the specs to run against.

```bash
$ bundle exec rake test_app
$ bundle exec rspec spec
```

Copyright (c) 2012 [John Hwang], released under the New BSD License
