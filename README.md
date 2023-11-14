# InterviewTopics
Let's gather our collective strength! 👯‍♀️👯‍♂️
Thank you :)

# Required
It is highly recommended to study the following content as much as possible 📝

+ If the interview is scheduled after WWDC (July~November), it's highly recommended to watch the WWDC sessions for that year.

[Apple All Videos](https://developer.apple.com/videos/all-videos/)

## iOS
- Explain the difference between Bounds and Frame.
- Explain what can and cannot be done in the development environment when there is no actual device.
- What is the special object for storing/approaching the content or data of an app?
- What is the object responsible for displaying and managing the logic of the app screen's content?
- Explain App Thinning.
###
- What object is created by the UIApplicationMain function in main.c when the app starts?
- Explain @Main.
- What constraints exist when the app is in the foreground and background?
- Explain the app delegate methods for handling different behaviors based on state changes.
- Describe the scenario when the app becomes In-Active.
- Explain the Scene Delegate.
- Where should the controller role of the UIApplication object be implemented?
- Explain the states of an app: Not running, Inactive, Active, Background, Suspended.
###
- What is the essential framework name for creating iOS apps and configuring the User Interface?
- What is Foundation Kit, and what classes does it include?
- Define Delegate, explain whether it retains or not, and provide the reasons.
- Explain the working mechanism and use cases of NotificationCenter.
- When dealing with UIKit classes, what is the application thread name that must be handled?
- Describe the structure and role of the App Bundle.
- What is the superclass of all View Controller objects, and what is its role?
- How to create a custom view, and what are the steps?
- Explain the concept of View in iOS.
- Describe the role of the Layer object in UIView.
- Explain the concept and differences between View and Layer in iOS.
- What is the role of the UIWindow object?
- Describe the role of UINavigationController.
- Explain the working mechanism of TableView and the minimum DataSource methods needed to display cells on the screen.
- If a single View Controller code needs to play multiple roles as TableView Controllers, how can it be implemented?
- Explain the differences between setNeedsLayout and setNeedsDisplay.
- Discuss the advantages and disadvantages of stackView.
###
- Explain the differences between NSCache and using a dictionary for caching.
- Describe URLSession.
- Explain prepareForReuse.
- Explain how to support Dark Mode.
- Describe the lifecycle of a ViewController.
- Explain the differences between TableView and CollectionView.
- Discuss the differences between Dynamic Library and Static Library.

## Autolayout
- What are the ways to write Auto Layout in code? (3 methods)
- Explain hugging and resistance.
- Explain Intrinsic Size.
- Discuss the pros and cons of using Storyboards.
- Explain Safe Area.
- Explain the differences between Left Constraint and Leading Constraint.
- What are the differences between Auto Layout and Frame-based Layout?
- Which debugging tools can be used to improve performance? When is each debugging tool suitable?

## Swift
- Explain the differences between struct, class, and enum.
- List ways to improve the performance of a class.
- Explain how Copy On Write works.
- Explain Convenience init.
- Explain AnyObject.
- Define Optional.
- Explain what a Struct is and how it is used.
- Explain Subscripts.
- Why can't you access String with subscripts?
- Explain the differences between instance methods and class methods.
- Explain the differences between class methods and static methods.
- Provide an example of using the Delegate pattern.
- Provide an example of using the Singleton pattern.
- Explain how KVO works.
- Explain the differences between Delegates and Notification patterns.
- Describe ways to consider when writing an app that operates in multiple threads.
- Draw a block diagram of the MVC structure and explain the roles and flow of each component.
- Explain what a Protocol is.
- Explain the differences between Protocol Oriented Programming and Object Oriented Programming.
- Explain what Hashable is and why Equatable should be inherited.
- Explain the mutating keyword.
- Explain escaping closures.
- Explain Extensions.
- Can you override a function within an Extension?
- Describe the types of access modifiers.
- Explain defer.
- Explain the order in which defer is called, and describe situations where defer is not called.
- Explain property wrappers.
- Explain Generics.
- Explain the some keyword.
- Explain Result type.
- Explain Codable.
- Explain Closures.
- Explain the relationship between Closures and functions.
- What are the differences between Optional Chaining and the nil-coalescing operator (??)? What are the precautions when using them?
- Before the introduction of Async/Await in Swift, what methods could be used to handle asynchronous tasks?
- Explain Type Casting and how Polymorphism is implemented in Swift.
- How is type safety ensured in Swift?

## ARC
- Explain what ARC is.
- Explain the Retain Count mechanism.
- Explain the Strong and Weak reference mechanisms.
- Explain Retain Cycles.
- In what cases does a Strong Reference Cycle occur?

## Functional Programming
- Explain what Pure Functions are.
- Explain what Functional Programming is.
- Explain what Higher-Order Functions are.
- Explain map, filter, reduce, compactMap, and flatMap in the Swift Standard Library.
- What is an Either type?

## Architecture
- Explain MVVM, MVI, Ribs, VIP, or any architecture you are familiar with.
- Explain Dependency Injection.

## SwiftUI
- Explain how @State works.

## Combine
- Explain PassthroughSubject.
- Explain @Published.
- Explain AnyCancellable.
- Explain sink.
- Explain the differences between throttle and debounce.
- Explain how to bind Data.

## Concurrency
### GCD, NSOperation
- Explain the differences between NSOperationQueue and GCD Queue.
- Explain the working mechanism and necessity of the GCD API.
- What types are there in the Qos of Global DispatchQueue, and what do they mean?

### Swift Concurrency
- When do you use @MainActor?
- Explain the working mechanism of tasks and the differences between GCD, NSOperation, and tasks.

# Optional
The following are additional topics that are good to study.

Objective-C or Rx usage may vary between companies and teams, and they might not be considered essential for junior or entry-level positions. Therefore, these are included as optional.

## Rx
- Explain what Reactive Programming is.
- Explain why RxSwift is used.
- Describe the disadvantages of RxSwift.
- Explain the differences between Hot Observable and Cold Observable in RxSwift.
- Explain the types of Subjects and their differences.
- Explain the differences between Subject and Driver.
- Explain the differences between Single, Completable, and Maybe, and when to apply each.
  
## MRC
- List the methods that must be used when implementing
