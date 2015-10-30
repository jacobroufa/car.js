# car.js

car.js is to be designed from the ground up to provide an evented structure within which to introduce tech-forward vehicle features. This will not deal with engine control at first. There will likely be some sort of OBD2/CAN readout but realistically providing dynamic inputs to the ECU and tuning on the fly isn’t on the immediate radar of this application. I also do not intend to have anything to do with safety features, namely airbags, though other security features (back-up camera or park distance sensors) will be considered.

At first this will be mostly a placeholder, as I record and start to organize my thoughts regarding the application’s structure and APIs. Documentation will hopefully provide a lot of help in that regard, so expect documents on various aspects of a vehicle’s electronic components.


## Motivation

I’ve wanted to put a computer in a car for years. I’ve never done it because of time and resources, but a large part is that I never had the capability to **truly** do things how I want. Being a programmer, though, I’ve learned that a great deal is possible. Node.js, and especially the [Johnny-Five framework](http://johnny-five.io/), provides a stable platform with which to affect the real world with JavaScript. So here I am, doing just that.


## Events

This system is basically a more well defined set of event handlers.


## Components

+ [Doors](docs/doors.md) (empty)
+ [Entertainment](docs/entertainment.md) (empty)
+ [Lights](docs/lights.md)
+ [Safety](docs/safety.md) (empty)


## Contributing
All contributions must adhere to the [Idiomatic.js Style Guide](https://github.com/rwaldron/idiomatic.js), by maintaining the existing coding style. Add unit tests for any new or changed functionality.


## License
Copyright (c) 2015 Jacob Roufa <jacob.roufa@gmail.com>
Licensed under the MIT license.
