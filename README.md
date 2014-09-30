# jwerty-rails

jwery-rails wraps the [jwerty.js](https://github.com/keithamus/jwerty) library in a rails engine for simple
use with the asset pipeline provided by rails 4.0. The gem includes the development (non-minified)
source for ease of exploration. The asset pipeline will minify in production.

jwerty is a JS lib which allows you to bind, fire and assert key combination strings against elements and events. It normalises the poor std api into something easy to use and clear. Please see the [documentation](https://github.com/keithamus/jwerty/blob/master/README-DETAILED.md) for details.

## Usage

Add the following to your gemfile:

    gem 'jwerty-rails'

Add the following directive to your Javascript manifest file (application.js):

    //= require jwerty

## Versioning

jwerty-rails 0.3.2 == jwerty.js 0.3.2
