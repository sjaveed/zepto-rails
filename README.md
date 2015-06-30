# zepto-rails

Zepto for the Rails asset pipeline.

This gem provides Zepto 1.1.6

## Installation

Add zepto-rails to the Gemfile.

```
gem 'zepto-rails', :github => 'packetman/zepto-rails'
```

And run `bundle install`.

Then add this lines to your `app/assets/javascripts/application.js`:

```
//= require zepto/default
```

If you only want to include some of the modules in zepto you can add them individually. The available modules are:

```
//= require 'zepto'
//= require 'zepto/event.js'
//= require 'zepto/ajax.js'
//= require 'zepto/form.js'
//= require 'zepto/ie.js'

//= require 'zepto/detect.js'
//= require 'zepto/fx.js'
//= require 'zepto/fx_methods.js'
//= require 'zepto/assets.js'
//= require 'zepto/data.js'
//= require 'zepto/selector.js'
//= require 'zepto/touch.js'
//= require 'zepto/gesture.js'
//= require 'zepto/stack.js'
//= require 'zepto/ios3.js'
//= require 'zepto/callbacks.js'
//= require 'zepto/deferred.js'
```

Or if you want to include all of the modules add this line to your `app/assets/javascripts/application.js`:

```
//= require zepto/all
```
