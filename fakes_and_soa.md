# Toggleable Mocks and Testing Strategies in a Service Oriented Architecture

## Abstract

Modern large scale applications often benefit from being composed of multiple smaller applications.  This can provide many benefits, but it can often make testing each piece more complex. I will cover a technique we use at Engine Yard to easily test these pieces individually and as a piece of the whole.

## Details

At Engine Yard, we write and use multiple smaller web apps that talk http to each other to comprise the larger application.  We each app with a client library that we use internally.  Each client library has two modes, a mocked mode and an unmocked mode and any application using these libraries can write tests against the library in either mode.

In normal development you simply run the tests in mocked mode which is quite fast.  But for the full integration tests, you can run the tests unmocked, which is much slower, but uses the same api as will be used in production.  This gives you significant confidence that the code is correct.
Appeal points (for example: the reason why this talk should be given at RubyKaigi2011) (English or Japanese / Used in selection) (optional): There are many benefits to using a "Service Oriented Architecture", but introducing more moving parts can add complexity.  I hear a lot about the benefits of using this architecture, but putting it into practice is often not discussed, especially in regards to testing.

### Submitted

* RubyKaigi
* Madison Ruby

### Accepted

* RubyKaigi