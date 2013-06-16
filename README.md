Yet Another NS API [![Build Status](https://travis-ci.org/stefanhendriks/ns-api.png?branch=master)](https://travis-ci.org/stefanhendriks/ns-api) [![Coverage Status](https://coveralls.io/repos/stefanhendriks/ns-api/badge.png)](https://coveralls.io/r/stefanhendriks/ns-api)
==================
A Ruby client for the NS API.



Usage
=====
First, make sure you have a username and password from the NS API website.
```ruby
# get username/password from NS site
client = NSClient.new("my-username", "my-password")

# get all known stations
client.stations
```

