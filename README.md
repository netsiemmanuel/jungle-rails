# Jungle

A mini e-commerce application built with Rails 6.1.

## Tech Stack

- Ruby
- Rails with ERB Templating
- PostgreSQL with Active Record ORM
- SCSS
- Bootstrap
- Testing: RSpec, cypress

## Final Product

## Products Page(Home)

!["Products Page(Home)"](https://github.com/netsiemmanuel/jungle-rails/blob/master/docs/jungle-prosucts-page.png?raw=true)

## Payment Page

!["Payment Page"](https://github.com/netsiemmanuel/jungle-rails/blob/master/docs/jungle-payment-page.png?raw=true)

## Setup

1. Run `bundle install` to install dependencies
2. Create `config/database.yml` by copying `config/database.example.yml`
3. Create `config/secrets.yml` by copying `config/secrets.example.yml`
4. Run `bin/rails db:reset` to create, load and seed db
5. Create .env file based on .env.example
6. Sign up for a Stripe account
7. Put Stripe (test) keys into appropriate .env vars
8. Run `bin/rails s -b 0.0.0.0` to start the server

## Stripe Testing

Use Credit Card # 4111 1111 1111 1111 for testing success scenarios.

More information in their docs: <https://stripe.com/docs/testing#cards>

## Dependencies

- Rails 6.1 [Rails Guide](http://guides.rubyonrails.org/v6.1/)
- Bootstrap 5
- PostgreSQL 9.x
- Stripe
