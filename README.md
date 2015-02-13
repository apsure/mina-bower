# Mina::Bower

Integrate bower into mina for deployment

## Installation

Add this line to your application's Gemfile:

    gem 'mina-bower'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install mina-bower

## Usage

In your deploy.rb add this

```
require 'mina/bower'
```

Then within your deploy task add this line to install bower depdenencies

```
invoke :'bower:install'
```

## Contributing

1. Fork it ( https://github.com/[my-github-username]/mina-bower/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
