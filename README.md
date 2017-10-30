<p align="center">
<img src="https://github.com/uber/ribs/blob/assets/rib_horizontal_black.png" width="450" height="196" alt="RIBs"/>
</p>

[![Build Status](https://travis-ci.org/uber/ios-template.svg?branch=master)](https://travis-ci.org/uber/ios-template)

RIBs is the cross-platform architecture behind many mobile apps at Uber. It was designed for large mobile applications with lots of volatile, server driven state, as well as large number of engineers working on one codebase.

The RIBs architecture provides:
* **Shared architecture across iOS and Android.** Build cross-platform apps that have similar architecture, enabling iOS and Android teams to cross-review business logic code.
* **Testability and Isolation.** Classes must be easy to unit test and reason about in isolation. Individual RIB classes have distinct responsibilities like: routing, business, view logic, creation. Plus, most RIB logic is decoupled from child RIB logic. This makes RIB classes easy to test and reason about independently.
* **Tooling for developer productivity.** RIBs come with IDE tooling around code generation, memory leak detection, static analysis and runtime integrations - all which improve developer productivity for large teams or small.
* **An architecture that scales.** This architecture has proven to scale to hundreds of engineers working on the same codebase and apps with hundreds of RIBs.


## Documentation
Refer to the [RIBs documentation](https://github.com/uber/RIBs/wiki) to get acquainted with key concepts and tutorials that run you through the all aspects of the architecture.


## Usage

1. Clone this repository 
2. Integrate using your preferred installation mechanism


## Installation for Android

TBD

```
dependencies {
  annotationProcessor 'com.uber.ribs:ribs:0.1.0'
  compile 'com.uber.ribs:ribs:0.1.0'
}
```

## Installation for iOS
#### CocoaPods

To integrate RIBs into your project add the following to your `Podfile`:

```ruby
pod 'RIBs', '~> 0.1'
```

#### Carthage

To integrate RIBs into your project using Carthage add the following to your `Cartfile`:

```ruby
github "uber/RIBs" ~> 0.1
```

## Contributions

We'd love for you to contribute to our open source projects. Before we can accept your contributions, we kindly ask you to sign our [Uber Contributor License Agreement](https://docs.google.com/a/uber.com/forms/d/1pAwS_-dA1KhPlfxzYLBqK6rsSWwRwH95OCCZrcsY5rk/viewform).

- If you **find a bug**, open an issue or submit a fix via a pull request.
- If you **have a feature request**, open an issue or submit an implementation via a pull request
- If you **want to contribute**, submit a pull request.

## License

    Copyright (C) 2017 Uber Technologies

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.