![CodeWars](https://www.codewars.com/users/Torlopov-Andrey/badges/large)

# iOS Developer Roadmap
</br></br>
## Archivements
* [HackerRank profile](https://www.hackerrank.com/Torlopov_andrey?hr_r=1)

[Unsorted links and articles](unsorted.md)

## Books

- [ ] [`Ray Wenderlich`]()
  - [X] Grosch S. - Concurrency by Tutorials (1st Edition) - 2019
  - [X] SwiftUI by Tutorials - 2020
  - [ ] Todorov M. - Realm. Building Modern Swift Apps with Realm Database (2nd Edition) - 2019
  - [ ] Animations by Tutorials - 2019
  - [ ] Greene J., Strawn J. - Design Patterns by Tutorials (3rd Edition) - 2019
- [X] Jon Hoffman. Swift 4. Protocol-oriented Programming

## ☑️ Memory manadgment  

  - [X] Stack and Heap
  - [X] Value vs Reference type
  - [X] ARC
  - [X] MRC
  - [X] Retain cycles
  - [X] Memory leaks
  - [X] [Autorelease pool](https://developer.apple.com/documentation/foundation/nsautoreleasepool?language=occ)
  - [X] Shallow and deep copying
  - [X] Weak/Strong references

## ☑️ Swift

- [X] Closures
- [X] Generic$#s
- [X] Initializers
- [X] Protocols
- [X] Struct
- [X] Enums
- [X] Runtime
- [X] Method dispatch

## ☑️ Multithreading and concurency

* [Concurrency vs Multi-threading vs Asynchronous Programming : Explained](https://habr.com/ru/post/337528/)
* [Многопоточность](https://habr.com/ru/post/320152/)

- [X] [`GCD`](https://medium.com/@alexey_nenastev/всё-о-многопоточности-в-swift-часть-1-настоящее-f0b4d5718877)
  - [X] Semaphors
  - [X] DispatchGroup
  - [X] DispatchWorkItem
  - [X] DispatchSource
- [X] NSOperationQueue
- [X] Race condition
- [X] Deadlock
- [X] Livelock
- [X] Readers/writers problem
- [X] [Green threads](https://ru.wikipedia.org/wiki/Green_threads)
- [X] Runloop

## ☑️ `UIKit`

- [X] UIApplication
- [X] UIApplication: States
- [X] [`UIViews`]()
  - [X] UITableViews
  - [X] UICollectionViews
- [X] [`Layout`]()
  - [X] Frame-based
  - [X] Autolayout
- [X] Navigation
- [X] UIViewController
- [X] UIViewController: Lifecycle

## ☑️ Networking

- [X] URLSession
- [X] Alamofire
- [X] Rest API
- [X] Difference between `GET`, `POST`, `PUT`, `PATCH`, `DELETE`

## ☑️ Foundation

- [X] Notifications vs Delegation vs Observing
- [X] Collections
- [X] Networking
- [X] [`Serialization`]()
  - [X] NSCoding
  - [X] Codable
  - [X] JSON
  - [X] XML
  
## ☑️ Software Architecture

* [clean architecture 1](https://hackernoon.com/introducing-clean-swift-architecture-vip-770a639ad7bf)
* [clear architecture 2](https://clean-swift.com/clean-swift-ios-architecture/)

- [X] MVC
- [X] MVVM
- [X] MVP
- [X] VIPER

## Design patterns

- [X] [`Creational`]()
  - [X] Factory
  - [X] Abstract Factory
  - [X] Builder
  - [X] Factory Method
  - [X] Prototype
  - [X] Object Pool
  - [X] Singleton
- [X] [`Structural`]()
  - [X] Adapter
  - [X] Bridge
  - [X] Composite
  - [X] Decorator
  - [X] Facade
  - [X] Flyweight
  - [X] Proxy
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
- [ ] [`Other`]()
  - [ ] Anti-pattern
  - [ ] Class cluster
  - [ ] Chain of Responsibility
  - [ ] Receptionist
  - [X] Template Method

## Design principles

- [ ] [`SOLID`]()
  - [X] Single responsibility principle
  - [X] Open/closed principle
  - [X] Liskov substitution principle
  - [ ] Interface segregation principle
  - [ ] Dependency inversion principle
- [X] Inversion of Control
- [X] Dependency Injection
- [X] Dry (don't repeat yourself)
- [X] KISS (keep it simple, stupid)

## ☑️ Dependency management

* [article #1](https://medium.com/ios-os-x-development/cocoapods-vs-carthage-675633e89c3e)
* [article #2](https://dzone.com/articles/carthage-or-cocoapods-that-is-the-question)

- [X] Cocoapods
- [X] Carthage
- [X] Swift Package Manager

## ☑️ Version Control System

- [X] git
- [X] SVN

## Caching and Presistency (2/4)

- [X] Core Data
- [X] Realm
- [ ] YAPDatabase
- [ ] SQLite

## Testing (3/5)

- [X] Unit Tests
- [ ] Snapshot Tests
- [ ] Functional test
- [X] TDD
- [X] BDD

## XCode/Tools/Debbuging (7/11)

- [ ] Workspace/cocoapods
- [X] Interface Builder
- [X] Keychain
- [ ] Security Transforms API
- [X] UI Debbuging
- [X] Reveal for UI Debuggin
- [X] Instruments: Leaks
- [X] Instruments: Time profiler
- [X] Instruments: Allocations
- [ ] Zombies
- [ ] Activity monitor  
- etc... 

## Continuous Integration (0/3)

- [ ] Fastlane
- [ ] Jenkins
- [ ] Xcode server

## Computer Science knowledge (2/22)

- [ ] Algorithms
  - [ ] Sorting
  - [ ] Graph Theory -> Trees
  - [ ] Strings

  - [ ] Greedy
  - [ ] Dynamic Programming
  - [ ] Bit Manipulation
  - [ ] Recursion
  - [ ] Game Theory
  - [ ] NP Complete
  - [X] Big-O notation
- [ ] [`Abstract Data Types`]()
  - [ ] Stack
  - [ ] Array
  - [ ] List
  - [ ] Map
  - [ ] Multimap
  - [ ] Set
  - [ ] Multiset (Bag)
  - [ ] Graph -> Tree
  - [X] Queue
  - [ ] Priority Queue
  - [ ] Double-ended priority queue
  - [ ] Double-ended queue

## Programming Paradigms (3/16)

  - [X] Protocol-Oriented 
  - [X] OOP
  - [ ] Functional
  - [ ] React Native
  - [ ] RxSwift
  - [ ] RxRealm, RxDataSources

## Libs, frameworks, pods, Kit's

- [X] ObjectMapper (pod)
- [X] Charts (pod)
- [X] Payments and subscription
- [X] Moya
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
  - [ ] Focus interactions
  - [ ] WatchKit
- [ ] [`TDD utils`]()
  - [ ] Specta
  - [ ] Expecta
  - [ ] OCMock

## ☑️ Course and tutorials

- [X] [Multithreading](https://swiftbook.ru)
- [X] [TDD](https://swiftbook.ru)

## Articles (43/127)

- [X] [Try to catch Zombie](https://oxozle.com/2016/01/25/lovim-zombi-obuekty-v-ios-xcode-ili-kak-reshat-message-sent-to-deallocated-instance/)
- [ ] [Apple Human Interface Guideline](https://developer.apple.com/design/human-interface-guidelines/ios/app-architecture/loading/)
- [X] [Structs and class](https://medium.com/commencis/stop-using-structs-e1be9a86376f)
- [ ] [Design patterns](https://refactoring.guru/ru/design-patterns/prototype)
- [X] [Swift styleguide](https://github.com/Torlopov-Andrey/swift-style-guide)
- [X] [@AUTORELEASEPOOL](http://en.swifter.tips/autoreleasepool/)
- [X] [Runloop](https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/Multithreading/RunLoopManagement/RunLoopManagement.html)
- [X] Blocks
- [X] Runtime
- [X] KVC
- [X] KVO- [X] NSZombies and KVO implementation
- [X] Swizzling
- [X] [Method Swizzling](http://nshipster.com/method-swizzling/)
- [X] [KVO Implementation Official Documentation](https://developer.apple.com/library/content/documentation/Cocoa/Conceptual/KeyValueObserving/Articles/KVOImplementation.html)
- [X] [KVO Implementation Analysis By MikeAsh](https://www.mikeash.com/pyblog/friday-qa-2009-01-23.html)
- [X] [Introduction to Key-Value Observing Programming Guide](https://developer.apple.com/library/content/documentation/Cocoa/Conceptual/KeyValueObserving/KeyValueObserving.html)
- [X] [Key-Value Observing](http://nshipster.com/key-value-observing/)
- [X] [About Key-Value Coding](https://developer.apple.com/library/content/documentation/Cocoa/Conceptual/KeyValueCoding/index.html)
- [X] [The Swift Programming Language: Closures](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/Closures.html)
- [X] [The Swift Programming Language: Enumerations](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/Enumerations.html)
- [X] [Generics in Swift 4](https://medium.com/developermind/generics-in-swift-4-4f802cd6f53c)
- [X] [Swift Generics Tutorial: Getting Started](https://www.raywenderlich.com/154371/swift-generics-tutorial-getting-started)
- [X] [The Swift Programming Language: Generics](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/Generics.html)
- [X] [Initialization In Depth, Part 1/2](https://www.raywenderlich.com/119922/swift-tutorial-initialization-part-1)
- [X] [Initialization In Depth, Part 2/2](https://www.raywenderlich.com/121603/swift-tutorial-initialization-part-2)
- [X] [Method Dispatch in Swift](https://www.raizlabs.com/dev/2016/12/swift-method-dispatch/)
- [X] [Separation of concerns using protocols in Swift](https://www.swiftbysundell.com/posts/separation-of-concerns-using-protocols-in-swift)
- [X] [Swift Optional Protocol Methods](https://useyourloaf.com/blog/swift-optional-protocol-methods/)
- [X] [The Swift Programming Language: Protocols](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/Protocols.html)
- [X] [How does iOS Swift Runtime work](https://stackoverflow.com/questions/37315295/how-does-ios-swift-runtime-work)
- [X] [The Swift Programming Language: Classes and Structures](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/ClassesAndStructures.html)
- [X] [The Foundation Collection Classes](https://www.objc.io/issues/7-foundation/collections/)
- [ ] [A Crash Course on Networking in iOS](https://www.sitepoint.com/a-crash-course-on-networking-in-ios/)
- [ ] >> [WHEN TO USE DELEGATION, NOTIFICATION, OR OBSERVATION IN IOS](https://shinesolutions.com/2011/06/14/delegation-notification-and-observation/)
- [ ] [Swift Codability](https://medium.com/@ravi.aggarwal61/swift-codability-d0d232065cad)
- [ ] [Swift Blog: Working with JSON in Swift](https://developer.apple.com/swift/blog/?id=37)
- [ ] [NSCoding / NSKeyed​Archiver](http://nshipster.com/nscoding/)
- [ ] [Introduction to Protocol Buffers on iOS](https://www.raywenderlich.com/149335/introduction-protocol-buffers-ios)
- [ ] [Foundation Framework](https://developer.apple.com/documentation/foundation)
- [ ] [Parallel programming with Swift: Basics](https://medium.com/flawless-app-stories/basics-of-parallel-programming-with-swift-93fee8425287)
- [ ] [Concurrent Programming](https://www.objc.io/issues/2-concurrency/)
- [ ] [Multithreading: Common Pitfalls](https://austingwalters.com/multithreading-common-pitfalls/)
- [ ] [NSOperation](http://nshipster.com/nsoperation/)
- [ ] [performSelector may cause a leak because its selector is unknown](https://stackoverflow.com/questions/7017281/performselector-may-cause-a-leak-because-its-selector-is-unknown)
- [ ] [Alternatives to performSelector](http://codeshaker.blogspot.co.uk/2012/05/alternatives-to-performselector.html)
- [X] [Wiki: Readers–writers problem](https://en.wikipedia.org/wiki/Readers%E2%80%93writers_problem)
- [X] [Dispatch Barriers in Swift 3](https://medium.com/@oyalhi/dispatch-barriers-in-swift-3-6c4a295215d6)
- [X] [Run Loops](https://developer.apple.com/library/content/documentation/Cocoa/Conceptual/Multithreading/RunLoopManagement/RunLoopManagement.html)
- [ ] [Synchronization](https://developer.apple.com/library/content/documentation/Cocoa/Conceptual/Multithreading/ThreadSafety/ThreadSafety.html)
- [ ] [Dependency Injection](https://www.objc.io/issues/15-testing/dependency-injection/)
- [ ] [Protocol Oriented Programming in Swift: An Introduction](https://www.appcoda.com/protocol-oriented-programming/)
- [ ] [Protocol-Oriented Programming in Swift](https://developer.apple.com/videos/play/wwdc2015/408/)
- [ ] [Basic iOS Security: Keychain and Hashing](https://www.raywenderlich.com/185370/basic-ios-security-keychain-hashing)
- [X] [The Three Laws of TDD](http://butunclebob.com/ArticleS.UncleBob.TheThreeRulesOfTdd)
- [X] [Behavior-Driven Testing Tutorial for iOS with Quick & Nimble](https://www.raywenderlich.com/182118/behavior-driven-testing-tutorial-ios-quick-nimble)
- [ ] [iOS Unit Testing and UI Testing Tutorial](https://www.raywenderlich.com/150073/ios-unit-testing-and-ui-testing-tutorial)
- [ ] [Singleton, Service Locator and tests in iOS](https://badootech.badoo.com/singleton-service-locator-and-tests-in-ios-d69484e88944)
- [ ] [Unit testing asynchronous Swift code](https://www.swiftbysundell.com/posts/unit-testing-asynchronous-swift-code)
- [X] [iOS User Interfaces: Storyboards vs. NIBs vs. Custom Code](https://www.toptal.com/ios/ios-user-interfaces-storyboards-vs-nibs-vs-custom-code)
- [ ] [Focus-Driven Interfaces with UIKit](https://developer.apple.com/videos/play/techtalks-apple-tv/3/)
- [ ] [The App Life Cycle](https://developer.apple.com/library/content/documentation/iPhone/Conceptual/iPhoneOSProgrammingGuide/TheAppLifeCycle/TheAppLifeCycle.html)
- [ ] [UIApplicationDelegate](https://developer.apple.com/documentation/uikit/uiapplicationdelegate)
- [ ] [Managing Your App's Life Cycle](https://developer.apple.com/documentation/uikit/core_app/managing_your_app_s_life_cycle)
- [ ] [UIApplication](https://developer.apple.com/documentation/uikit/uiapplication)
- [ ] [Understand the View Controller Lifecycle](https://developer.apple.com/library/content/referencelibrary/GettingStarted/DevelopiOSAppsSwift/WorkWithViewControllers.html)
- [ ] [The Role of View Controllers](https://developer.apple.com/library/content/featuredarticles/ViewControllerPGforiPhoneOS/)
- [ ] [Custom Collection View Layouts](https://www.objc.io/issues/3-views/collection-view-layouts/)
- [ ] >> [Clean Table View Code](https://www.objc.io/issues/1-view-controllers/table-views/)
- [ ] [UIView Fundamentals](https://www.weheartswift.com/uiview-fundamentals/)
- [ ] [objc.io Animations](https://www.objc.io/issues/12-animations/)
- [ ] [The Ultimate Guide To IOS AutoLayout](https://digitalleaves.com/ultimate-guide-autolayout/)
- [ ] [Understanding Autolayout Constraints In Depth](https://medium.com/@ravi.aggarwal61/understanding-auto-layout-constraints-part-1-844474e81d1e)
- [ ] [CGGeometry](http://nshipster.com/cggeometry/)
- [ ] [CALayer Tutorial for iOS: Getting Started](https://www.raywenderlich.com/169004/calayer-tutorial-ios-getting-started)
- [ ] [Demystifying iOS Layout](http://tech.gc.com/demystifying-ios-layout/)
- [ ] [Improve your iOS Architecture with FlowControllers](http://merowing.info/2016/01/improve-your-ios-architecture-with-flowcontrollers/)
- [ ] [Screen navigation in iOS](https://badootech.badoo.com/screen-navigation-in-ios-dd99b09228b2)
- [ ] [Introduction To UIStackView](https://www.raywenderlich.com/160646/uistackview-tutorial-introducing-stack-views-2)
- [ ] [Understanding UIView transform property (part 1)](https://ninjapro.wordpress.com/2016/08/23/understanding-uiviews-transform-property-part-1/)
- [ ] [Understanding UIView transform property (final)](https://ninjapro.wordpress.com/2016/08/27/understanding-uiviews-transform-property-final-part/)
- [ ] [UIKit Framework](https://developer.apple.com/documentation/uikit)
- [ ] [How to make friends with UIKit](https://badootech.badoo.com/how-to-make-friends-with-uikit-934ea431ffef)
- [ ] [UIKit fundamentals](https://eg.udacity.com/course/uikit-fundamentals--ud788)
- [X] [Pro Git](https://git-scm.com/book/en/v2)
- [ ] [Friday Q&A 2015-12-11: Swift Weak References](https://www.mikeash.com/pyblog/friday-qa-2015-12-11-swift-weak-references.html)
- [X] [Beginning ARC in iOS 5 Tutorial Part 1](https://www.raywenderlich.com/5677/beginning-arc-in-ios-5-part-1)
- [X] [Swift’s ARC and Memory Leaks](https://medium.com/ios-seminar/swifts-arc-and-memory-leaks-1a227cae55da)
- [X] [Memory Management Tutorial for iOS](https://www.raywenderlich.com/2657/memory-management-tutorial-for-ios)
- [X] [Retain Cycles, Weak and Unowned in Swift](http://www.thomashanning.com/retain-cycles-weak-unowned-swift/)
- [X] [Object copying](https://developer.apple.com/library/content/documentation/CoreFoundation/Conceptual/CFMemoryMgmt/Concepts/CopyFunctions.html)
- [ ] [Stack and Heap Objects in Objective-C](https://www.mikeash.com/pyblog/friday-qa-2010-01-15-stack-and-heap-objects-in-objective-c.html)
- [ ] [Stack vs Heap](https://tproger.ru/translations/programming-concepts-stack-and-heap/)
- [ ] [Articles #2](http://microsin.net/programming/pc/dot-net-stack-heap-value-reference-boxing-unboxing.html)
- [ ] [About Memory Management](https://developer.apple.com/library/content/documentation/Cocoa/Conceptual/MemoryMgmt/Articles/MemoryMgmt.html)
- [ ] [How do reference counting and garbage collection compare?](https://www.quora.com/How-do-reference-counting-and-garbage-collection-compare)
- [ ] [RIBs](https://eng.uber.com/new-rider-app/)
- [ ] [Clean architecture with RxSwift](https://github.com/sergdort/CleanArchitectureRxSwift)
- [ ] [Stanford MVC](https://web.stanford.edu/class/cs75n/1_MVC.pdf)
- [ ] [Do MVC like it’s 1979](https://badootech.badoo.com/do-mvc-like-its-1979-da62304f6568)
- [ ] [iOS Architecture Patterns](https://medium.com/ios-os-x-development/ios-architecture-patterns-ecba4c38de52)
- [ ] [Designing iOS architecture: Motivation](https://medium.com/@borlov/e984e4ebba4a)
- [ ] [Designing iOS architecture: Checklist](https://github.com/BohdanOrlov/architecture-checklist)
- [ ] [Class Clusters](https://developer.apple.com/legacy/library/documentation/Cocoa/Conceptual/CocoaFundamentals/CocoaObjects/CocoaObjects.html#//apple_ref/doc/uid/TP40002974-CH4-SW34)
- [ ] [Cocoa Design Patterns](https://developer.apple.com/legacy/library/documentation/Cocoa/Conceptual/CocoaFundamentals/CocoaDesignPatterns/CocoaDesignPatterns.html)
- [ ] [Collection for Design Patterns in Swift](https://medium.com/swiftworld/collection-for-design-patterns-in-swift-67265359aa47)
- [ ] [Instruments Tutorial with Swift: Getting Started](https://www.raywenderlich.com/166125/instruments-tutorial-swift-getting-started)
- [ ] [Carthage Tutorial: Getting Started](https://www.raywenderlich.com/165660/carthage-tutorial-getting-started-2)
- [ ] [CocoaPods Tutorial for Swift: Getting Started](https://www.raywenderlich.com/156971/cocoapods-tutorial-swift-getting-started)
- [ ] [Swift Package Manager](https://swift.org/package-manager/)
- [ ] [Core Data Programming Guide](https://developer.apple.com/library/content/documentation/Cocoa/Conceptual/CoreData/index.html)
- [ ] [Core Data from Scratch: Concurrency](https://code.tutsplus.com/tutorials/core-data-from-scratch-concurrency--cms-22131)
- [X] [Realm](https://realm.io/docs/swift/latest)
- [ ] [iOS Location Tracking](https://badootech.badoo.com/ios-location-tracking-aac4e2323629)
- [ ] [Core Motion](https://developer.apple.com/documentation/coremotion)
- [ ] [Health and Fitness with Core Motion](https://developer.apple.com/videos/play/wwdc2016/713/)
- [ ] [Creating Immersive Apps with Core Motion](https://developer.apple.com/videos/play/wwdc2017/704/)
- [ ] [UserNotifications in Swift 3 (Part 1)](https://medium.com/yay-its-erica/usernotifications-in-swift-3-part-1-d250e54440c1)
- [ ] [Background Modes Tutorial: Getting Started](https://www.raywenderlich.com/143128/background-modes-tutorial-getting-started)
- [ ] [Big O notation](https://en.wikipedia.org/wiki/Big_O_notation)
- [ ] [Swift Algorithm Club: Boyer Moore String Search Algorithm](https://www.raywenderlich.com/163964/swift-algorithm-club-booyer-moore-string-search-algorithm)
- [X] [Swift Algorithm Club](https://github.com/raywenderlich/swift-algorithm-club)
- [ ] [Algorithms Specialization](https://www.coursera.org/specializations/algorithms)
- [ ] [Interactive diagrams of Rx Observables](http://rxmarbles.com)
- [X] [Structures in Swift](https://medium.com/swift-india/part1-struct-2d585269b121)
- [X] [Copy-On-Write](https://dzone.com/articles/use-copy-on-write-with-swift-value-types-1)
- [X] [GCD](https://medium.com/@alexey_nenastev/всё-о-многопоточности-в-swift-часть-1-настоящее-f0b4d5718877)

## Appendix

- [ ] HTTP timeouts
- [X] Когда удаляются autorelease объекты
- [ ] Unsafe Swift
- [ ] Лицензирование (Licenses)
- [ ] SSH
- [ ] Increase FPS
- [ ] Decrease memory footprint
- [ ] Protobuf
- [ ] Work in background mode
- [ ] [Learning Path: RxSwift from Start to Finish](https://academy.realm.io/posts/learning-path-rxswift-from-start-to-finish/)
- [ ] [fastlane Tutorial: Getting Started](https://www.raywenderlich.com/136168/fastlane-tutorial-getting-started-2)
- [ ] [Fastlane](https://fastlane.tools)
- [ ] [Objective-C Runtime Programming Guide](https://developer.apple.com/library/content/documentation/Cocoa/Conceptual/ObjCRuntimeGuide/Introduction/Introduction.html)
- [ ] [Obj-Runtime](https://m.habr.com/ru/post/177421)
- [ ] [How Objective-C messaging works](http://dantoml.com/how-objective-c-messaging-works/)
- [ ] [Friday Q&A 2013-02-08: Let's Build Key-Value Coding](https://www.mikeash.com/pyblog/friday-qa-2013-02-08-lets-build-key-value-coding.html)
- [ ] [Friday Q&A 2009-08-14: Practical Blocks](https://www.mikeash.com/pyblog/friday-qa-2009-08-14-practical-blocks.html)
- [ ] [How blocks are implemented (and the consequences)](https://www.cocoawithlove.com/2009/10/how-blocks-are-implemented-and.html)
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



<br><br>

![Skills matrix](matrix.png)

## Контакты для связи:
* skype: torlopov.andrey
* email: [torlopov.andrey@gmail.com](mailto:torlopov.andrey@gmail.com)
* github: [https://github.com/Torlopov-Andrey](https://github.com/Torlopov-Andrey)



<!-- **Progress: ◽◽◽◽◽◽◽◽◽  0.0001%** -->
