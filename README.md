# Decidim::Clave

Decidim omniauth sign up and sign in with Cl@ve.

## Installation

Install the gem and add to the application's Gemfile by executing:

    $ bundle add decidim-clave
    $ bundle install

## Usage

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and the created tag, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Run tests

Node 16.9.1 is required!

Create a dummy app:

```bash
bin/rails decidim:generate_external_test_app
```

And run tests:

```bash
bundle exec rspec spec
```


## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/decidim-clave. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [code of conduct](https://github.com/[USERNAME]/decidim-clave/blob/master/CODE_OF_CONDUCT.md).

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the Decidim::Clave project's codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/[USERNAME]/decidim-clave/blob/master/CODE_OF_CONDUCT.md).