# Rubocop::Config::Prettier

Turns off all rules that are unnecessary or might conflict with
[prettier plugin ruby](https://github.com/prettier/plugin-ruby).

`config/awesomecode-rubocop.yml` works for [our
fork](https://github.com/xinminlabs/plugin-ruby).

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'rubocop-config-prettier'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install rubocop-config-prettier

## Usage

Add the following code to your rubocop config file.

```
inherit_gem:
  rubocop-config-prettier: config/rubocop.yml
```

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/xinminlabs/rubocop-config-prettier.
