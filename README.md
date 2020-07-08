# example-quickstart

Simple example app with [Percy](https://percy.io) visual regression tests.

## Usage:

```bash
$ git clone https://github.com/percy/example-quickstart.git
$ cd example-quickstart/

$ export PERCY_TOKEN=67f8ec1338860c427cbea0e37c8559203a2742993a9c3623a7a493033c3c48ee
$ export PERCY_API=http://dev.percy.local:9090/api/v1
$ gem install bundler  # Only if you don't have bundler installed.
$ bundle install

$ bundle exec ruby visual-tests.rb
```

testing codeship
