# Improving Inter Service Communication

## Short Description
In times where applications get more and more split up into small pieces that have to communicate with each other it's critical to have systems in place that make this communication as trouble-free as possible. This talk covers what we did at Engine Yard to improve our inter service communication and how you can apply that to your own infrastructure.

## Abstract
This talk tells the story on how we have improved the way to build and maintain web services at Engine Yard with the introduction of an internal PUBSUB infrastructure. The wise UNIX philosophers are telling us "Write programs that do one thing and do it well". And even decades after this wisdom was born it's still as fresh and true as in it's early days, now that monolithic web applications are being replaces more and more by sets of small services that work together. This is a good first step in the right direction but we are still failing at how we implement most web services with a strong coupling to mutual API contracts between each other.

The introduction of a PUBSUB infrastructure for the first time gives us the power to change that. I will give a look behind the scenes at Engine Yard and talk share insights on our PUBSUB setup from the bare metal to client libraries, documentation and tools involved. In a second part I will cover how all that changed the way we are developing services and eased the way to realize new ideas.

## About me:

I am Thorben, former founder of “kopfmaschine”, a German Rails shop located in Bremen and now working to make the cloud a better place for developers at Engine Yard in San Francisco. I am living and breathing Ruby since my days at University where I graduated with my thesis on how to scale large Rails applications.

### Pending

* [Mountain West Ruby 2012](http://mtnwestrubyconf.org/)
* [OSCON 2012](http://www.oscon.com/oscon2012)
* [RubyConf India 2012](http://rubyconfindia.org/2012/)
* [Nordic Ruby 2012](http://nordicruby.org/)

### Accepted

### Not accepted
* [Madison Ruby 2012](http://madisonruby.org/)
* [Ruby on Ales 2012](http://ruby.onales.com/)