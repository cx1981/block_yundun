# BlockYundun

[![Gem Version](https://img.shields.io/gem/v/block_yundun.svg)](https://img.shields.io/gem/v/block_yundun.svg)
[![Build Status](https://travis-ci.org/42thcoder/block_yundun.svg?branch=master)](https://travis-ci.org/42thcoder/block_yundun)
[![Code Coverage](https://img.shields.io/codecov/c/github/42thcoder/block_yundun.svg?branch=master)](https://img.shields.io/codecov/c/github/42thcoder/block_yundun.svg)
[![Code Climate](https://img.shields.io/codeclimate/github/kabisaict/flow.svg)](https://img.shields.io/codeclimate/github/kabisaict/flow.svg)

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'block_yundun'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install block_yundun

## Usage

Add `app.middleware.use Rack::BlockYundun` to `config/production.rb` and your world is finally in peace.

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/42thcoder/block_yundun.

## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
