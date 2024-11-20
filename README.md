# dynamic-obfuscating

Dynamic obfuscation is a project that takes obfuscation to a more secure and dynamic level by giving users the capability to generate obfuscation and deobfuscation strategy using obfuscation definition.

___

## Table of content

- [Problem Being Solved](#problem-being-solved)
- [The Obfuscating Engine](#the-obfuscating-engine)
    - [Obufuscation Definition](#obufuscation-definition)
    - [Obfuscation And Deobfuscation Function](#obfuscation-and-deobfuscation-function)
- [Implementing the Obfuscation Engine](#implementing-the-obfuscation-engine)
- [Debugging](#debugging)
- [Application And Use Cases](#application-and-use-cases)
    - [Api Request](#api-request)
    - [Offline Licensing](#Offline Licensing)
    - [Secure Data Communication](#secure-data-communication)
- [Contributing](#contributing)
- [License](#license)


## Problem Being Solved

In industries or applications where data require the most privacy and security if the data is being transported from one location to another the data is still exposed through the network with the hope that the user device is not compromised. A solution for such is to use encryption that requires iv and keys but this kind of method is still to some extent not very secure as the encryption details still needs to be stored on the client side which still make is available for attackers to access the encrypted data. 

With the solution introduced by this project users will have the capability to generate obfuscation strategy on the fly in application scope and even on a single request scope, the project will also makes it easy to generate obfuscation strategy that is unique, and the strength will also depends on the obfucation definition.


## The Obfuscating Engine 

The obfuscating engine are components that are involve in the parsing and processing of the obfuscation strategy definition, generating the method for obfuscation and de obfuscation.


### Obufuscation Definition

The obfuscation definition is the text that is passed to the obfuscation engine which produces the obfuscation and deobfudcation methods, the obfucation definition is to the engine as a source code is to programming language.


### Obfuscation And Deobfuscation Function

After processing the obfuscation definition two functions are generated for the user in specified programming langauge, the two functions can be copied into user project or used directly from the engine implementation.


## Implementing the Obfuscation Engine

Implementation of the engine is planned to be across all main stream programming language to give the user the capability to obfuscate in a backend language (C#, java e.t.c) and deobfuscate in a frontend/client based langugae like Javascript.


## Debugging

For the purpose of debugging the obfuscation, browser extensions will be created for main browsers to make it easy for users to debug their API request for use case where the data from and to backend is obfuscated.


## Application And Use Cases


### Api Request


### Offline Licensing


### Secure Data Communication


## Contributing

If you have any issue or you want to request a feature you can open a request [here](https://github.com/exoticlibraries/libcester/issues/new/choose) anytime and if you made some changes that should be added to the main project send in a [pull request](https://github.com/exoticlibraries/libcester/compare). 

## License

MIT License Copyright (c) 2024 