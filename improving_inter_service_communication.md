# Improving Inter Service Communication

## Short Description

In times when applications get more and more split up into small pieces that have to communicate with each other it's critical to have systems in place that make this communication as trouble-free as possible. This talk covers what we did at Engine Yard to improve our inter service communication and how you can apply that to your own infrastructure.

## Abstract

This talk tells the story on how we have improved the way to build and maintain web services at Engine Yard with the introduction of an internal PUBSUB infrastructure. The wise UNIX philosophers tell us "Write programs that do one thing and do it well". Decades after this wisdom was born, it's still as fresh and true as in it's early days, especially now that monolithic web applications are being replaced more and more by sets of small services that work together. This is a good first step in the right direction, but unfortunately we are failing at how we implement web services when a strong coupling to mutual API contracts between each other remains.

The introduction of a PUBSUB infrastructure gives us the power to change that. I will give you a look behind the scenes at Engine Yard and share insights on our PUBSUB setup from the bare metal to client libraries, documentation, and tools involved. In a second part, I will cover how this can change the way you are developing services, make building new ideas easier, and how it can make you a better developer.


## About me:

I am Thorben, former founder of “kopfmaschine”, a German Rails shop located in Bremen and now working to make the cloud a better place for developers at Engine Yard in San Francisco. I am living and breathing Ruby since my days at University where I graduated with my thesis on how to scale large Rails applications.

### Pending
* [Aloha Ruby 2012](http://aloharubyconf.com/)

### Accepted
* [RubyConf India 2012](http://rubyconfindia.org/2012/)
* [Red Dot Ruby 20212](http://reddotrubyconf.com/)
* [RULU 2012](https://rulu.eu)

### Not accepted
* [Ruby on Ales 2012](http://ruby.onales.com/)
* [Mountain West Ruby 2012](http://mtnwestrubyconf.org/)
* [Nordic Ruby 2012](http://nordicruby.org/)
* [Madison Ruby 2012](http://madisonruby.org/)
* [OSCON 2012](http://www.oscon.com/oscon2012)
* [Scotish Ruby Conference 2012](http://cfp.scottishrubyconference.com/)