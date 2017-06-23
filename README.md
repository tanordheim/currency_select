# CurrencySelect

[![Build Status](https://travis-ci.org/oliverklee/currency_select.svg?branch=master)](https://travis-ci.org/oliverklee/currency_select)
[![Gem Version](https://badge.fury.io/rb/currency_select.svg)](http://badge.fury.io/rb/currency_select)

Adds a currency_select helper to Ruby on Rails projects, allowing you to get
a HTML select list of available currencies.

The list of currencies are provided by the [Money](http://money.rubyforge.org/)
gem.


## Installation

Add the following to your Gemfile

gem 'currency_select', github: 'tanordheim/currency_select'


## Example

    currency_select("user", "currency")

## Copyright

Copyright (c) 2010 Trond Arve Nordheim. See LICENSE for details.
