# Decent Authentication
[![Build Status](https://secure.travis-ci.org/leesmith/decent_authentication.png?branch=master)](http://travis-ci.org/leesmith/decent_authentication) [![Code Climate](https://codeclimate.com/github/leesmith/decent_authentication.png)](https://codeclimate.com/github/leesmith/decent_authentication)

Decent Authentication is a sample application that implements authentication in Rails 3.2 without the use of a third-party generator or engine.  This is essentially a complete reproduction of [Ryan Bates' Authentication from Scratch railscast](http://railscasts.com/episodes/250-authentication-from-scratch-revised) with my addition of RSpec unit and integration tests. In addition to authentication, features include rememberable cookie and password reset.

See the 'rails-3.0' tag for a legacy Rails 3.0 implementation.

## Dependencies

* Ruby 1.9+

## Getting Started

```
git clone git@github.com:leesmith/decent_authentication.git
cd decent_authentication
./bin/setup
./bin/rake
```
