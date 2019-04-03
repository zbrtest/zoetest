# example-quickstart

Simple example app with [Percy](https://percy.io) visual regression tests.

## Usage:

```bash
$ git clone https://github.com/percy/example-quickstart.git
$ cd example-quickstart/

for Zoe/very-soft, locally:
$ export PERCY_TOKEN=39b3da3a1fa9f5019218cb075fae4dc78392cb56371395550714c120d3f4590f
$ export PERCY_API=http://dev.percy.local:9090/api/v1
$ gem install bundler  # Only if you don't have bundler installed.
$ bundle install

$ bundle exec ruby visual-tests.rb
```
