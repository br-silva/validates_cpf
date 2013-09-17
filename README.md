# ValidatesCPF 

[![Gem Version](https://badge.fury.io/rb/validates_cpf.png)](http://badge.fury.io/rb/validates_cpf) [![Build Status](https://secure.travis-ci.org/plribeiro3000/validates_cpf.png?branch=master)](http://travis-ci.org/plribeiro3000/validates_cpf) [![Dependency Status](https://gemnasium.com/plribeiro3000/validates_cpf.png)](https://gemnasium.com/plribeiro3000/validates_cpf) [![Coverage Status](https://coveralls.io/repos/plribeiro3000/validates_cpf/badge.png?branch=master)](https://coveralls.io/r/plribeiro3000/validates_cpf)  [![Code Climate](https://codeclimate.com/github/plribeiro3000/validates_cpf.png)](https://codeclimate.com/github/plribeiro3000/validates_cpf)

Rails gem to validate CPF. Don't forget to check {ValidatesCnpj}[https://github.com/plribeiro3000/validates_cnpj], {ValidatesTelephone}[https://github.com/plribeiro3000/validates_telephone] and {ValidatesHost}[https://github.com/plribeiro3000/validates_host].

## Installation

Add this line to your application's Gemfile:

    gem 'validates_cpf'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install validates_cpf

## Usage

Lets say you have a model with "cpf" string column that you want to be a valid CPF. Just add this to your model:

 class User < ActiveRecord::Base
    validates :cpf, :cpf => true
 end

## Notes

It will load a macher to test automatically if the gem is below shoulda-matchers.

## Mantainers
[@plribeiro3000](https://github.com/plribeiro3000)

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request