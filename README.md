# Polyfills

The main goal of this repo is to keep track of all the polyfills that
need to be created as `npm` modules in order to be easy to reuse in
different projects.  

Also another important reason is provide an easy workflow to provide
support to [`ES5`](http://www.ecma-international.org/ecma-262/5.1/#sec-10.1.1) and
previous versions that does not support new functions.

# What's a Polyfill by the way?

A Polyfill in a nutshell is just a piece of code that runs if the
browser does not support a certain functionality or function in certain
versions by adding the code for that functionality in the cases where is
required, so we can make sure we provide for older browsers.   

![](http://www.paulirish.com/i/7570.png)  
By [Paul Irish](http://www.paulirish.com/)  

[Another great article](https://remysharp.com/2010/10/08/what-is-a-polyfill) that
explains in depth about the same topic.

# Array

- [Array.prototype.find](https://github.com/jsPolyfill/Array.prototype.find)
- [Array.prototype.findIndex](https://github.com/jsPolyfill/Array.prototype.findIndex)

# Collaboration

You can collaborate by creating a new issue with the missing Polyfill, it 
will be really appreciated. Thank you.

Thank you.
