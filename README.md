# ☑️ iOS Developer Roadmap

**Progress: ◼◼◼◼◼◽◽◽◽◽  51%**

## Languages

- [ ] [`Objective-C`]()
  - [X] [Blocks](src/objc/blocks.md)
  - [ ] Runtime
  - [X] [KVC](src/objc/KVC.md)
  - [X] [KVO](src/objc/KVO.md)
  - [ ] [Toll-free bridging](src/objc/toll-free-bridging.md)
  - [ ] [Runtime](src/objc/objc_runtime.md)
  - [ ] [Method messaging](src/objc/method_messaging.md)
  - [ ] [NSZombies and KVO implementation](src/objc/NSZombies.md)
  - [ ] [Swizzling](src/objc/swizzling.md)
- [X] [`Swift`](src/swift/swift.md)
  - [X] [Closures](src/swift/swift_closure.md)
  - [X] [Generics](src/swift/swift_generics.md)
  - [X] [Initializers](src/swift/swift_initializers.md)
  - [X] [Protocols](src/swift/swift_protocol.md)
  - [X] [Struct](src/swift/swift_struct.md)
  - [X] [Enums](src/swift/swift_enum.md)
  - [ ] [Runtime](src/swift/swift_runtime.md)
  - [ ] [Method dispatch](src/swift/swift_method_dispatch.md)

## Memory manadgment

  - [ ] Stack and Heap
  - [X] Value vs Reference type
  - [X] ARC
  - [X] MRC
  - [X] Retain cycles
  - [X] Memory leaks
  - [ ] Autorelease pool
  - [ ] Shallow and deep copying
  - [X] Weak/Strong references

## Multithreading and concurency

- [X] [GCD](src/multithreading/CGD.md)
- [ ] NSOperation[Queue]
- [ ] [Runloop](src/multithreading/runloop.md)
- [ ] [Synchronization](src/multithreading/synchronization.md)
- [ ] [POSIX and NSThreads](src/multithreading/POSIX_and_NSThreads.md)
- [ ] [Perform selector family](src/multithreading/perform_selector_family.md)
- [X] [Race condition](src/multithreading/race_condition.md)
- [X] [Deadlock](src/multithreading/deadlock.md)
- [X] Livelock
- [ ] [Readers/writers problem](src/multithreading/readers–writers_problem.md)


## Cocoa touch
- [X] [`UIKit`](src/uikit/uikit.md)
  - [X] [UIApplication](src/uikit/UIApplication/RESOURCES.md)
  - [X] [UIApplication: States](src/uikit/UIApplication/States/RESOURCES.md)
  - [X] [UIViews](src/uikit/UIViews/RESOURCES.md)
    - [X] [UITableViews](src/uikit/UIViews/UITableViews/RESOURCES.md)
    - [X] [UICollectionViews](src/uikit/UIViews/UICollectionViews/RESOURCES.md)
  - [X] [Layout](src/uikit/layout.md)
    - [X] [Frame-based](src/uikit/frame-based.md)
    - [X] [Autolayout](src/uikit/autolayout.md)
  - [X] [Navigation](src/uikit/navigation.md)
  - [X] [UIViewController](src/uikit/UIViewController/RESOURCES.md)
  - [X] [UIViewController: Lifecycle](src/uikit/UIViewController/Lifecycle/RESOURCES.md)
  - [ ] [Animations](src/uikit/animations.md)
  - [ ] [Transform](src/uikit/transform.md)

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

## Software Architecture

- [ ] [`Design patterns`]()
  - [ ] [Architectural](src/Software_Architecture/Design_Patterns/Architectural/RESOURCES.md)
    - [X] [MVC](src/Software_Architecture/Design_Patterns/Architectural/MVC/RESOURCES.md)
    - [X] [MVVM](src/Software_Architecture/Design_Patterns/Architectural/MVVM/RESOURCES.md)
    - [X] MVP
    - [ ] [Clean architecture](src/Software_Architecture/Design_Patterns/Architectural/Clean_architecture/RESOURCES.md)
    - [X] [VIPER](src/Software_Architecture/Design_Patterns/Architectural/Clean_architecture/VIPER/RESOURCES.md)
    - [ ] [RIBs](src/Software_Architecture/Design_Patterns/Architectural/Clean_architecture/RIBs/RESOURCES.md)
    - [ ] [Coordinators](src/Software_Architecture/Design_Patterns/Architectural/Coordinators/RESOURCES.md)
  - [ ] Abstract Factory
  - [ ] [Class cluster](src/Software_Architecture/Design_Patterns/Cocoa/Abstract_Factory/Class_cluster/RESOURCES.md)
  - [X] Adapter
  - [X] Command Pattern
  - [ ] Chain of Responsibility
  - [ ] [`Decorator`]()
      - [X] Delegation
      - [ ] Categories
  - [X] Facade
  - [ ] Memento
  - [X] Observer
  - [ ] Proxy
  - [ ] Receptionist
  - [X] Singleton
  - [X] Template Method

- [X] [`Design principles`]()
  - [X] [`SOLID`](src/Software_Architecture/Design_Principles/SOLID/RESOURCES.md)
    - [X] Single responsibility principle
    - [X] Open/closed principle
    - [X] Liskov substitution principle
    - [X] Interface segregation principle
    - [X] Dependency inversion principle
  - [X] Inversion of Control
  - [X] Dependency Injection
  - [X] Dry (don't repeat yourself)
  - [X] KISS (keep it simple, stupid)
  - [ ] [`Creational`]()
    - [X] Factory
    - [X] Abstract Factory
    - [ ] Builder
    - [X] Factory Method
    - [ ] Object Pool
    - [ ] Prototype
    - [X] [Singleton](src/Software_Architecture/Design_Patterns/Creational/Singleton/RESOURCES.md)
  - [ ] [`Structural`]()
    - [X] Adapter
    - [X] Bridge
    - [X] Composite
    - [X] Decorator
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
  - [ ] Concurrency
    - [ ] Anti-pattern

## Dependency management

- [X] [Cocoapods](src/Dependencies_management/Cocoapods/RESOURCES.md)
- [ ] [Carthage](src/Dependencies_management/Carthage/RESOURCES.md)
- [ ] [Swift Package Manager](src/Dependencies_management/Swift_Package_Manager/RESOURCES.md)

## Version Control System
- [X] git
  
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
- [ ] [Core Data](src/Caching_and_Persistency/Core_Data/RESOURCES.md)
- [ ] [Realm](src/Caching_and_Persistency/Realm/RESOURCES.md)
- [ ] YAPDatabase

## Testing

- [X] [Unit Tests](src/Testing/Unit_Tests/RESOURCES.md)
- [ ] Snapshot Tests
- [ ] Functional test
- [X] [TDD](src/Testing/TDD/RESOURCES.md)
- [ ] [BDD](src/Testing/BDD/RESOURCES.md)

## Performance optimization
  - [ ] Increase FPS
  - [ ] Decrease memory footprint
- [ ] [`Code signing`]()
  - [ ] [`Tools`]()
    - [ ] [`IDE`]()
      - [ ] [`Xcode`]()
        - [ ] [Interface Builder](src/Tools/IDE/Xcode/Interface_Builder/RESOURCES.md)
        - [X] Swiftlint
        - [ ] Sourcery
        - [ ] [Fastlane](src/Tools/Fastlane/RESOURCES.md)
    - [ ] [`Continuous Integration`]()
      - [ ] Jenkins
      - [ ] Xcode server
    - [ ] [`Security`]()
      - [ ] [Keychain](src/Security/Keychain/RESOURCES.md)
      - [ ] Security Transforms API
    - [ ] [`tvOS`]()
        - [ ] [Focus interactions](src/tvOS/Focus_interactions/RESOURCES.md)
    - [ ] [WatchKit]()

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
  - [ ] [Problems](src/Computer_Science_knowledge/System_design/Problems/RESOURCES.md)

## Programming Paradigms
  - [X] Protocol-Oriented 
  - [X] Object-Oriented
  - [ ] Functional
  - [ ] [`Functional Reactive Programming Frameworks`]()
    - [ ] React Native
    - [ ] [RxSwift](src/Computer_Science_knowledge/Programming_Paradigms/Functional/Functional_Reactive_Programming_Frameworks/RxSwift/RESOURCES.md)
    - [ ] RxRealm, RxDataSources
## Libs and frameworks
- [ ] [`Network`]()
  - [X] Alamofire
  - [X] ObjectMapper
- [`Graphics`]()
  - [X] Charts
- [X] Payments and subscription

<br><br>
# ⚙ Addon
![Skills matrix](https://github.com/BohdanOrlov/ios-skills-matrix/raw/master/matrix.png)
