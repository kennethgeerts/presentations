# What you (and I) should do
---
## Disclaimer: "SHOULD"
### (No I don't always do this but I should)
---
## (for developers)
---
## Why this reminder?
---
## Getting rid of bad code
- It's your job to make stuff better
- Shouldn't ask for permission for this
---
## Pointers to good resources to improve code
### Very very very basic, simple stuff
---
## 1. to read
---
## Ruby style guide
### https://github.com/bbatsov/ruby-style-guide
---
## Rails style guide
### https://github.com/bbatsov/rails-style-guide
---
## Numerous blogs
### Look for them
---
## 2. to listen
---
## The Bike Shed
### http://bikeshed.fm/
#### Ruby / Rails / practical problems
#### episodes with Katrina Owen / Sandi Metz
---
## So here is the simple stuff we do wrong
---
### Lousy comments
#### (imprecise, wrong, obvious)
---
### Commented Out Code
---
### Trailing Whitespace

#### Set Sublime Text to
`"trim_trailing_white_space_on_save": true`

#### (Your Favourite Editor™ will have a setting)
---
### Also:
`"ensure_newline_at_eof_on_save": true`
`"translate_tabs_to_spaces": true`
---
### `to_s` in string interpolation
---
### Explicit default parameters
```ruby
def explicit_default_arguments
  [1, 2, 3].join('')
end
```
---
### Beware of dependencies
### Beware of too many gems
---
## ❝SHUT UP, AREN'T THERE MORE URGENT PROBLEMS?❞
---
Getting the simple things right will make your life better and makes it easier to focus on the hard stuff!
---
