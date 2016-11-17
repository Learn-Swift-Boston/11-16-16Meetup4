# 11-16-16Meetup4

In the 11/16/16 meetup, we learned a lot about optionals and error handling.

## Optionals
An optional variable is one that allows for the [absence of value](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/TheBasics.html#//apple_ref/doc/uid/TP40014097-CH5-ID330). It is most commonly represented by the `?` operator. If you want to force unwrap an optional, you can use `!`. However force unwrapping should generally be avoided unless you are positive the value of your variable will be present (or want you app to crash should the value be missing).

Further explanation can be found:
* https://medium.com/ios-os-x-development/swift-optionals-78dafaa53f3#.fnkorrikm

## Error Handling
Apple has made error handling a first class citizen in Swift. Creating a `try` statement in a `do-catch` block allows you to properly handling failing code (see Optionals above). If a function `throws` you want your code to `catch` it so that errors can properly be handled, in a graceful way, so that either the user or developer knows when something has gone wrong.

Further explanation can be found:
* https://www.raywenderlich.com/130197/magical-error-handling-swift
