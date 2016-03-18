# Testing in Ruby on Rails

## The Book

I'm currently reading [Everyday Rails Rspec](https://leanpub.com/everydayrailsrspec)

The goal is to formalize testing strategies.  Currently, my preference
is to use integration tests to test the happy path through an application
but then unit test all the containing pieces to flesh out any edge cases.

View tests are good to prevent too many feature specs that slow down the
test suite.

## The Hope

Eventually gaining a more fine grained understanding about what tests work
best in which situations.  My current approach seems a bit broad.