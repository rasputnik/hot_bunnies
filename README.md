# Hot Bunnies, a JRuby RabbitMQ Client

Hot Bunnies is an idiomatic, fast and well-maintained (J)Ruby DSL on top of the [RabbitMQ Java client](http://www.rabbitmq.com/api-guide.html). It strives to combine
strong parts of the Java client with over 3 years of [Ruby amqp gem](https://github.com/ruby-amqp/amqp) development experience.

## Why Hot Bunnies

 * Concurrency support on the JVM is excellent, with many tools & approaches available. Lets make use of it.
 * RabbitMQ Java client is rock solid and supports every RabbitMQ feature. Very nice.
 * It is screaming fast thanks to all the heavy duty being done in the pretty efficient & lightweight Java code.
 * It uses synchronous APIs where it makes sense and asynchronous APIs where it makes sense. Some other [Ruby RabbitMQ clients](https://github.com/ruby-amqp)
   only use one or the other.
 * [amqp gem](https://github.com/ruby-amqp/amqp) has certain amount of baggage it cannot drop because of backwards compatibility concerns. Hot Bunnies is a
   clean room design, much more open to radical new ideas.
 * Someone just *had* to come up with a library called Hot Bunnies. Are your bunnies hot?


## What Hot Bunnies is not

Hot Bunnies is not

 * A replacement for the RabbitMQ Java client
 * An attempt to re-create 100% of the amqp gem API on top of the Java client
 * A "work queue" like Resque
 * A cure for cancer


## Installation, Dependency

### With Rubygems

    gem install hot_bunnies

### With Bundler

    gem "hot_bunnies", "~> 1.5.0"


## Documentation

HotBunnies currently does not have documentation guides like [amqp gem](http://rubyamqp.info) or [Bunny](http://rubybunny.info).

Several [code examples](examples) are available. Our [test suite](spec/integration) also has many code examples
that demonstrate various parts of the API.


## Supported JDK Versions

HotBunnies is tested against OpenJDK 7, Oracle JDK 7 and is
known to work well on OpenJDK 6 and Sun JDK 6.


## Change Log

See [ChangeLog.md](ChangeLog.md).


## Continuous Integration

[![Continuous Integration status](https://secure.travis-ci.org/ruby-amqp/hot_bunnies.png)](http://travis-ci.org/ruby-amqp/hot_bunnies)

CI is hosted by [travis-ci.org](http://travis-ci.org)


## License

MIT, see LICENSE in the repository root


## Copyright

Theo Hultberg, Michael Klishin, 2011-2013.
