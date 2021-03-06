# Message Queue. Development Repository

[![Gitter](https://badges.gitter.im/php-enqueue/Lobby.svg)](https://gitter.im/php-enqueue/Lobby)
[![Build Status](https://travis-ci.org/php-enqueue/enqueue-dev.png?branch=master)](https://travis-ci.org/php-enqueue/enqueue-dev)
[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE)

This is where all development happens. The repository provides a friendly environment for productive development and testing of all enqueue related packages.

Features:

* [Feature rich](docs/quick_tour.md).
* Implements [JMS](https://docs.oracle.com/javaee/7/api/javax/jms/package-summary.html) like transports based on [queue-interop](https://github.com/queue-interop/queue-interop) interfaces.
* Supported  transports 
    * [AMQP(s)](docs/transport/amqp.md) based on [PHP AMQP extension](https://github.com/pdezwart/php-amqp). 
[![Build Status](https://travis-ci.org/php-enqueue/amqp-ext.png?branch=master)](https://travis-ci.org/php-enqueue/amqp-ext)
[![Total Downloads](https://poser.pugx.org/enqueue/amqp-ext/d/total.png)](https://packagist.org/packages/enqueue/amqp-ext)
[![Latest Stable Version](https://poser.pugx.org/enqueue/amqp-ext/version.png)](https://packagist.org/packages/enqueue/amqp-ext)
    * [AMQP](docs/transport/amqp_bunny.md) based on [bunny](https://github.com/jakubkulhan/bunny). 
[![Build Status](https://travis-ci.org/php-enqueue/amqp-bunny.png?branch=master)](https://travis-ci.org/php-enqueue/amqp-bunny)
[![Total Downloads](https://poser.pugx.org/enqueue/amqp-bunny/d/total.png)](https://packagist.org/packages/enqueue/amqp-bunny)
[![Latest Stable Version](https://poser.pugx.org/enqueue/amqp-bunny/version.png)](https://packagist.org/packages/enqueue/amqp-bunny)
    * [AMQP(s)](docs/transport/amqp_lib.md) based on [php-amqplib](https://github.com/php-amqplib/php-amqplib). 
[![Build Status](https://travis-ci.org/php-enqueue/amqp-lib.png?branch=master)](https://travis-ci.org/php-enqueue/amqp-lib)
[![Total Downloads](https://poser.pugx.org/enqueue/amqp-lib/d/total.png)](https://packagist.org/packages/enqueue/amqp-lib)
[![Latest Stable Version](https://poser.pugx.org/enqueue/amqp-lib/version.png)](https://packagist.org/packages/enqueue/amqp-lib)
    * [Beanstalk](docs/transport/pheanstalk.md).
[![Build Status](https://travis-ci.org/php-enqueue/pheanstalk.png?branch=master)](https://travis-ci.org/php-enqueue/pheanstalk)
[![Total Downloads](https://poser.pugx.org/enqueue/pheanstalk/d/total.png)](https://packagist.org/packages/enqueue/pheanstalk)
[![Latest Stable Version](https://poser.pugx.org/enqueue/pheanstalk/version.png)](https://packagist.org/packages/enqueue/pheanstalk)
    * [STOMP](docs/transport/stomp.md)
[![Build Status](https://travis-ci.org/php-enqueue/stomp.png?branch=master)](https://travis-ci.org/php-enqueue/stomp)
[![Total Downloads](https://poser.pugx.org/enqueue/stomp/d/total.png)](https://packagist.org/packages/enqueue/stomp)
[![Latest Stable Version](https://poser.pugx.org/enqueue/stomp/version.png)](https://packagist.org/packages/enqueue/stomp)
    * [Amazon SQS](docs/transport/sqs.md)
[![Build Status](https://travis-ci.org/php-enqueue/sqs.png?branch=master)](https://travis-ci.org/php-enqueue/sqs)
[![Total Downloads](https://poser.pugx.org/enqueue/sqs/d/total.png)](https://packagist.org/packages/enqueue/sqs)
[![Latest Stable Version](https://poser.pugx.org/enqueue/sqs/version.png)](https://packagist.org/packages/enqueue/sqs)
    * [Google PubSub](docs/transport/gps.md)
[![Build Status](https://travis-ci.org/php-enqueue/gps.png?branch=master)](https://travis-ci.org/php-enqueue/gps)
[![Total Downloads](https://poser.pugx.org/enqueue/gps/d/total.png)](https://packagist.org/packages/enqueue/gps)
[![Latest Stable Version](https://poser.pugx.org/enqueue/gps/version.png)](https://packagist.org/packages/enqueue/gps)
    * [Kafka](docs/transport/kafka.md)
[![Build Status](https://travis-ci.org/php-enqueue/rdkafka.png?branch=master)](https://travis-ci.org/php-enqueue/rdkafka)
[![Total Downloads](https://poser.pugx.org/enqueue/rdkafka/d/total.png)](https://packagist.org/packages/enqueue/rdkafka)
[![Latest Stable Version](https://poser.pugx.org/enqueue/rdkafka/version.png)](https://packagist.org/packages/enqueue/rdkafka)
    * [Redis](docs/transport/redis.md)
[![Build Status](https://travis-ci.org/php-enqueue/redis.png?branch=master)](https://travis-ci.org/php-enqueue/redis)
[![Total Downloads](https://poser.pugx.org/enqueue/redis/d/total.png)](https://packagist.org/packages/enqueue/redis)
[![Latest Stable Version](https://poser.pugx.org/enqueue/redis/version.png)](https://packagist.org/packages/enqueue/redis)
    * [Gearman](docs/transport/gearman.md)
[![Build Status](https://travis-ci.org/php-enqueue/gearman.png?branch=master)](https://travis-ci.org/php-enqueue/gearman)
[![Total Downloads](https://poser.pugx.org/enqueue/gearman/d/total.png)](https://packagist.org/packages/enqueue/gearman)
[![Latest Stable Version](https://poser.pugx.org/enqueue/gearman/version.png)](https://packagist.org/packages/enqueue/gearman)
    * [Doctrine DBAL](docs/transport/dbal.md)
[![Build Status](https://travis-ci.org/php-enqueue/dbal.png?branch=master)](https://travis-ci.org/php-enqueue/dbal)
[![Total Downloads](https://poser.pugx.org/enqueue/dbal/d/total.png)](https://packagist.org/packages/enqueue/dbal)
[![Latest Stable Version](https://poser.pugx.org/enqueue/dbal/version.png)](https://packagist.org/packages/enqueue/dbal)
    * [Filesystem](docs/transport/filesystem.md)
[![Build Status](https://travis-ci.org/php-enqueue/fs.png?branch=master)](https://travis-ci.org/php-enqueue/fs)
[![Total Downloads](https://poser.pugx.org/enqueue/fs/d/total.png)](https://packagist.org/packages/enqueue/fs)
[![Latest Stable Version](https://poser.pugx.org/enqueue/fs/version.png)](https://packagist.org/packages/enqueue/fs)
    * [Null](docs/transport/null.md).
[![Build Status](https://travis-ci.org/php-enqueue/null.png?branch=master)](https://travis-ci.org/php-enqueue/null)
[![Total Downloads](https://poser.pugx.org/enqueue/null/d/total.png)](https://packagist.org/packages/enqueue/null)
[![Latest Stable Version](https://poser.pugx.org/enqueue/null/version.png)](https://packagist.org/packages/enqueue/null)
* [Symfony bundle](https://github.com/php-enqueue/enqueue-dev/blob/master/docs/bundle/quick_tour.md)
* [Magento1 extension](https://github.com/php-enqueue/enqueue-dev/blob/master/docs/magento/quick_tour.md)
* [Laravel extension](https://github.com/php-enqueue/enqueue-dev/blob/master/docs/laravel/quick_tour.md)
* [Message bus](http://www.enterpriseintegrationpatterns.com/patterns/messaging/MessageBus.html) support.
* [RPC over MQ](https://www.rabbitmq.com/tutorials/tutorial-one-php.html) support.
* Temporary queues support.
* Well designed components decoupled and reusable.
* Carefully tested including unit and functional tests.
* For more visit [quick tour](docs/quick_tour.md).

## Resources

* [Quick tour](https://github.com/php-enqueue/enqueue-dev/blob/master/docs/quick_tour.md)
* [Documentation](https://github.com/php-enqueue/enqueue-dev/blob/master/docs/index.md)
* [Blog](https://github.com/php-enqueue/enqueue-dev/blob/master/docs/index.md#blogs)
* [Questions](https://gitter.im/php-enqueue/Lobby)
* [Issue Tracker](https://github.com/php-enqueue/enqueue-dev/issues)

## Developed by Forma-Pro

Forma-Pro is a full stack development company which interests also spread to open source development. 
Being a team of strong professionals we have an aim an ability to help community by developing cutting edge solutions in the areas of e-commerce, docker & microservice oriented architecture where we have accumulated a huge many-years experience. 
Our main specialization is Symfony framework based solution, but we are always looking to the technologies that allow us to do our job the best way. We are committed to creating solutions that revolutionize the way how things are developed in aspects of architecture & scalability.

If you have any questions and inquires about our open source development, this product particularly or any other matter feel free to contact at opensource@forma-pro.com

## License

It is released under the [MIT License](LICENSE).
