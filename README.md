# iOS Developer Roadmap

**Progress: ◼◼◼◼◼◼◽◽◽◽  61.7%**

## ☑️ Memory manadgment  

  - [X] [Stack and Heap](src/memory/stack_heap/RESOURCES.md)
  - [X] Value vs Reference type
  - [X] ARC
  - [X] MRC
  - [X] Retain cycles
  - [X] Memory leaks
  - [X] [Autorelease pool](https://developer.apple.com/documentation/foundation/nsautoreleasepool?language=occ)
  - [X] Shallow and deep copying
  - [X] Weak/Strong references

## ▶ Swift

  - [X] [Closures](src/language/swift/swift_closure.md)
  - [X] [Generics](src/language/swift/swift_generics.md)
  - [X] [Initializers](src/language/swift/swift_initializers.md)
  - [X] [Protocols](src/language/swift/swift_protocol.md)
  - [X] [Struct](src/language/swift/swift_struct.md)
  - [X] [Enums](src/language/swift/swift_enum.md)
  - [X] [Runtime](src/language/swift/swift_runtime.md)
  - [ ] [Method dispatch](src/language/swift/swift_method_dispatch.md)

## Multithreading and concurency
* [Concurrency vs Multi-threading vs Asynchronous Programming : Explained](https://habr.com/ru/post/337528/)
  
- [X] [`GCD`](https://medium.com/@alexey_nenastev/всё-о-многопоточности-в-swift-часть-1-настоящее-f0b4d5718877)
  - [X] Semaphors
  - [X] DispatchGroup
  - [X] DispatchWorkItem
  - [X] DispatchSource
- [X] NSOperationQueue
- [ ] [Runloop](src/multithreading/runloop.md)
- [ ] [Synchronization](src/multithreading/synchronization.md)
- [ ] [Perform selector family](src/multithreading/perform_selector_family.md)
- [X] Race condition
- [X] Deadlock
- [X] Livelock
- [X] [Readers/writers problem](src/multithreading/readers–writers_problem.md)
- [X] [Green threads](https://ru.wikipedia.org/wiki/Green_threads)

## ☑️ [`UIKit`](src/uikit/uikit.md)

- [X] [UIApplication](src/uikit/UIApplication/RESOURCES.md)
- [X] [UIApplication: States](src/uikit/UIApplication/States/RESOURCES.md)
- [X] [`UIViews`](src/uikit/UIViews/RESOURCES.md)
  - [X] [UITableViews](src/uikit/UIViews/UITableViews/RESOURCES.md)
  - [X] [UICollectionViews](src/uikit/UIViews/UICollectionViews/RESOURCES.md)
- [X] [`Layout`](src/uikit/layout.md)
  - [X] [Frame-based](src/uikit/frame-based.md)
  - [X] [Autolayout](src/uikit/autolayout.md)
- [X] [Navigation](src/uikit/navigation.md)
- [X] [UIViewController](src/uikit/UIViewController/RESOURCES.md)
- [X] [UIViewController: Lifecycle](src/uikit/UIViewController/Lifecycle/RESOURCES.md)

## ☑️ Networking
- [X] URLSession
- [X] Alamofire
- [X] [Rest API](src/networking/rest_api.md)
- [X] Difference between `GET`, `POST`, `PUT`, `PATCH`, `DELETE`

## Foundation

- [X] [Notifications vs Delegation vs Observing](src/foundation/Notifications_vs_Delegation_vs_Observing/RESOURCES.md)
- [ ] [Collections](src/foundation/Collections/RESOURCES.md)
- [X] [Networking](src/foundation/Networking/RESOURCES.md)
- [ ] [`Serialization`](src/foundation/Serialization/RESOURCES.md)
  - [X] [NSCoding](src/foundation/Serialization/NSCoding/RESOURCES.md)
  - [X] [Codable](src/foundation/Serialization/Codable/RESOURCES.md)
  - [X] [JSON](src/foundation/Serialization/JSON/RESOURCES.md)
  - [X] [XML](src/foundation/Serialization/XML/RESOURCES.md)
  - [ ] [Protobuf](src/foundation/Serialization/Protobuf/RESOURCES.md)
- [ ] Work in background mode

## ☑️ Software Architecture

* [clean architecture 1](https://hackernoon.com/introducing-clean-swift-architecture-vip-770a639ad7bf)
* [clear architecture 2](https://clean-swift.com/clean-swift-ios-architecture/)

- [X] MVC
- [X] MVVM
- [X] MVP
- [X] Clean architecture
- [X] VIPER

## [Design patterns](https://refactoring.guru/ru/design-patterns/prototype)

- [X] [`Creational`]()
  - [X] Factory
  - [X] Abstract Factory
  - [X] Builder
  - [X] Factory Method
  - [X] Prototype
  - [X] [Object Pool](http://cpp-reference.ru/patterns/creational-patterns/object-pool/)
  - [X] Singleton
- [ ] [`Structural`]()
  - [X] Adapter
  - [X] Bridge
  - [X] Composite
  - [X] [`Decorator`]()
    - [ ] Delegation
    - [ ] Categories
  - [X] Facade
  - [ ] Flyweight
  - [ ] Proxy
- [ ] [`Behavioural`]()
  - [X] Command
  - [ ] Chain of responsibility
  - [ ] Interpreter
  - [ ] Iterator
  - [ ] Mediator
  - [ ] Memento
  - [X] Observer
  - [X] State
  - [X] Strategy
  - [ ] Visitor
- [ ] ['Other']()
  - [ ] Anti-pattern
  - [ ] [Class cluster](src/Design_Patterns/Cocoa/Abstract_Factory/Class_cluster/RESOURCES.md)
  - [ ] Chain of Responsibility
  - [ ] Receptionist
  - [X] Template Method

## Design principles

- [X] [`SOLID`](src/Design_Principles/SOLID/RESOURCES.md)
  - [X] Single responsibility principle
  - [X] Open/closed principle
  - [X] Liskov substitution principle
  - [X] Interface segregation principle
  - [X] Dependency inversion principle
- [X] Inversion of Control
- [X] Dependency Injection
- [X] Dry (don't repeat yourself)
- [X] KISS (keep it simple, stupid)

## Dependency management

* [article #1](https://medium.com/ios-os-x-development/cocoapods-vs-carthage-675633e89c3e)
* [article #2](https://dzone.com/articles/carthage-or-cocoapods-that-is-the-question)

- [X] [Cocoapods](src/Dependencies_management/Cocoapods/RESOURCES.md)
- [X] [Carthage](src/Dependencies_management/Carthage/RESOURCES.md)
- [ ] [Swift Package Manager](src/Dependencies_management/Swift_Package_Manager/RESOURCES.md)

## ☑️ Version Control System

- [X] git
- [X] SVN
  
## Debugging

- [ ] [`Instruments`](src/Debugging/Instruments/RESOURCES.md)
  - [X] Leaks
  - [X] Time profiler
  - [ ] Zombies
  - [ ] Activity monitor
  - [ ] Allocations
  - [ ] etc... 
- [ ] [Swift styleguide](https://github.com/Torlopov-Andrey/swift-style-guide)

## Caching and Presistency

- [X] [Core Data](src/Caching_and_Persistency/Core_Data/RESOURCES.md)
- [X] [Realm](src/Caching_and_Persistency/Realm/RESOURCES.md)
- [ ] YAPDatabase

## Testing

- [X] [Unit Tests](src/Testing/Unit_Tests/RESOURCES.md)
- [ ] Snapshot Tests
- [ ] Functional test
- [X] [TDD](src/Testing/TDD/RESOURCES.md)
- [X] [BDD](src/Testing/BDD/RESOURCES.md)

## Tools

- [X] [Interface Builder](src/Tools/IDE/Xcode/Interface_Builder/RESOURCES.md)    
- [ ] [`Continuous Integration`]()
  - [ ] [Fastlane](src/Tools/Fastlane/RESOURCES.md)
  - [ ] Jenkins
  - [ ] Xcode server
- [ ] [`Security`]()
  - [X] [Keychain](src/Security/Keychain/RESOURCES.md)
  - [ ] Security Transforms API

## Computer Science knowledge

- [ ] [`Algorithms`](src/Computer_Science_knowledge/Algorithms/RESOURCES.md)
  - [ ] Sorting
  - [ ] [`Graph Theory`]()
    - [ ] Trees
  - [ ] [Strings](src/Computer_Science_knowledge/Algorithms/Strings/RESOURCES.md)
  - [ ] Greedy
  - [ ] Dynamic Programming
  - [ ] Bit Manipulation
  - [X] Recursion
  - [ ] Game Theory
  - [ ] NP Complete
  - [X] [Big-O notation](src/Computer_Science_knowledge/Algorithms/Big-O_notation/RESOURCES.md)
- [ ] [`Abstract Data Types`]()
  - [X] Stack
  - [X] Array
  - [X] List
  - [X] Map
  - [ ] Multimap
  - [X] Set
  - [ ] Multiset (Bag)
  - [ ] Graph
      - [ ] Tree
  - [X] Queue
  - [ ] Priority Queue
  - [ ] Double-ended priority queue
  - [ ] Double-ended queue

## Programming Paradigms

  - [X] Protocol-Oriented 
  - [X] [Object-Oriented](src/program_paradigm/oop.md)
  - [ ] Functional
  - [ ] [`Functional Reactive Programming Frameworks`]()
    - [ ] React Native
    - [ ] [RxSwift](src/Computer_Science_knowledge/Programming_Paradigms/Functional/Functional_Reactive_Programming_Frameworks/RxSwift/RESOURCES.md)
    - [ ] RxRealm, RxDataSources

## Libs, frameworks, pods, Kit's

- [X] ObjectMapper (pod)
- [X] Charts (pod)
- [X] Payments and subscription
- [ ] BLE (Bluetooth Low Energy)
- [ ] AVFoundation
- [ ] AVKit
- [ ] ARKit
- [ ] HomeKit
- [ ] MedKit
- [ ] MapKit
- [ ] YandexMap
- [ ] [`Animations`]()
  - [ ] Core Graphics
  - [ ] Core Animation
  - [ ] Transformation
- [ ] [`tvOS`]()
  - [ ] [Focus interactions](src/tvOS/Focus_interactions/RESOURCES.md)
  - [ ] [WatchKit]()
- [ ] [`TDD utils`]()
  - [ ] Specta
  - [ ] Expecta
  - [ ] OCMock

## Books 

- [ ] [`Ray Wenderlich`]()
  - [ ] RxSwift&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;◼◼◼◽◽◽◽◽◽◽ 33%
  - [ ] Animations&nbsp;◼◽◽◽◽◽◽◽◽◽ 14%
- [X] Jon Hoffman. Swift 4. Protocol-oriented Programming

## Course and tutorials

- [X] [Multithreading](https://swiftbook.ru)
- [X] [TDD](https://swiftbook.ru)

## Additional topics

- [ ] Лицензирование (Licenses)
- [ ] SSH
- [ ] [POSIX and NSThreads](src/multithreading/POSIX_and_NSThreads.md)
- [ ] Increase FPS
- [ ] Decrease memory footprint

## Questions (RUS)
- [ ] Таймауты для HTTP запросов
- [ ] Когда удаляются autorelease объекты

## Problems

- [ ] generate a unique ID for each URL?
- [ ] How would you generate unique IDs at scale (thousands of URL shortening requests coming every second)?
- [ ] How would your service handle redirects?
- [ ] How would you support custom short URLs?
- [ ] How to delete expired URLs etc?
- [ ] How to track click stats?
- [ ] How would you record stats about videos e.g the total number of views, up-votes/down-votes, etc.
- [ ] How would a user add comments on videos (in realtime)
- [ ] How would you design one-on-one conversations between users?
- [ ] How would you extend your design to support group chats?
- [ ] What to do when the user is not connected to the internet?
- [ ] When to send push notifications?
- [ ] Can you provide end-to-end encryption. How?
- [ ] Records stats for each answer e.g. the total number of views, upvotes/downvotes, etc.
- [ ] Users should be able to follow other users or topics
- [ ] Their timeline will consist of top questions from all the users and topics they follow (similar to newsfeed generation).
- [ ] How would users be able to upload/view/search/share files or photos?
- [ ] How would you track persmissions for file sharing
- [ ] How would you allow multiple users to edit the same document
- [ ] Efficient storage and search for posts or tweets.
- [ ] Newsfeed generation
- [ ] Social Graph (who befriends whom or who follows whom — specially when millions of users are following a celebrity)
- [ ] The most critical use case — when a customer requests a ride and how to efficiently match them with the nearby drivers?
- [ ] How to store millions of geographical locations for drivers and riders who are always moving.
- [ ] How to handle updates to driver/rider locations (millions of updates every second)?
- [ ] How to store previous search queries?
- [ ] How to keep the data fresh?
- [ ] How to find the best matches to the already typed string?
- [ ] How to handle updates and the user is typing too fast?


## Objective-C

  - [X] [Blocks](src/language/objc/blocks.md)
  - [ ] Runtime
  - [X] [KVC](src/language/objc/KVC.md)
  - [X] [KVO](src/language/objc/KVO.md)
  - [ ] [Runtime](src/language/objc/objc_runtime.md)
  - [ ] [Method messaging](src/language/objc/method_messaging.md)
  - [ ] [NSZombies and KVO implementation](src/language/objc/NSZombies.md)
  - [ ] [Swizzling](src/language/objc/swizzling.md)

## Temp

- [ ] [RIBs](src/Software_Architecture/Design_Patterns/Architectural/Clean_architecture/RIBs/RESOURCES.md)
- [ ] Sourcery


<br><br>

![Skills matrix](https://github.com/BohdanOrlov/ios-skills-matrix/raw/master/matrix.png)

<br><br>


## Контакты для связи:
* skype: torlopov.andrey
* email: [torlopov.andrey@gmail.com](mailto:torlopov.andrey@gmail.com)
* github: [https://github.com/Torlopov-Andrey](https://github.com/Torlopov-Andrey)
