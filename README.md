Rails Backbone Stripe Membership Saas
================

This application is to test a Stripe Membership Saas with Rails, using Backbone.js as frontend.



Ruby on Rails
-------------

This application requires:

- Ruby 2.1.2
- Rails 4.2.3

And uses the usual suspects gems, as:

gem 'devise'
gem 'bootstrap-sass'
gem 'payola-payments'
gem 'upmin-admin'

Getting Started
---------------

Git clone, then bundle install, migrate, seed and rails server. Open http://localhost:3000/

Isn't easy?

Well, before seeding, add your Stripe keys to secrets.

```
bundle install
rake db:migrate
rake db:seed
rails s
```

If you want to use PG or MySql, add the gems, set the database.yml, migrate and good to go.

For Stripe API keys, and login details too, modify the secrets file.

Documentation and Support
-------------------------

This is it!

Issues
-------------

Find them, please. And notify them.

Similar Projects
----------------

Composer + Backbone!

Contributing
------------

Just fork and done.

Credits
-------

@altuzar

License
-------

Do whatever you want.