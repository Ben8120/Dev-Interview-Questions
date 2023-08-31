1. What is iOS?
iOS is a sotware platform that runs on Apple's iPhone lineup of devices. iOS is intended to be more power-efficient, quicker and smaller. OS stands for Operating System, and iOS is is maintained and developed by Aple Inc. and published exclusively for Apple hardware iPhone.
Notable features of iOS includes:
 - Integrated search capability
 - Device shaking
 - Navigation tools
 - Closed-source Operating System
 - iCloud Service
 - Notification Center

2. What are the abstraction levels of iOS? (also known as iOS Architecture)
There are four different abstraction levels of iOS:

 - Core OS Layer: It provides low-level capabilities and security framworks for interacting with external hardware.
 - Core Serice Layer: This provides services the top layer requires from the core services layer.
 - Media Layer: Offers tools required for graphics, audio, and video.
 - Cocoa Touch Layer: Location for frameworks, frequently used while designing applications.

 3. Differentiate between asynchronous and synchronous calls.
 Synchronous API calls entails pausing the code execution and waiting for the API call to complete. This means your application won't continue to run until the API returns a response, which the user may experience as latency or performance lag. However, synchronous API calls can be advantageous if your app functions only once the API response has been received.

 Asynchronous calls do not wait for the server to respond to the API calls. Your program continues to run, and a "callback" function is then called when the server responds to the call.

 4. What are properties in iOS?
 A property is used mainly when other objects need to change or access the ivars in your object, without manually defining getters and setters. They can be further classified into **Stored Properties** and **Computed Properties**

**Stored Properties** store constant and variable values as part of an instance, they are provided only by **Classes** and **Structure**.
**Computed Properties** _calculate_ a value, they are provided by classes, structures and enumerations.

5. What are enums?
A variable with an enum symbol can only take one of a set of predetermined values, such as a day of the week. Consequently, a list of all potential values must be provided when declaring an enum.

7. What is code coverage?
Code Coverage calculates how much your production code ran while your automated test suite was being run. It is usually stated as a percentage of lines that were actually executed out of all the lines that could be performed. It provides a general indication of "how well tested" your code is and, thus, "how certain we may be that it will operate."

8. What are different aplication states in iOS?
iOS has five application states:
**Not Running**
The system shut down the app, whether it had already started or not.

**Inactie**
Despite being active in the foreground, the app is not currently getting events. A typical app only spends a short time in this stage before moving on to another.

**Active**
The application is getting events while it is active in the foreground. The default setting for foreground apps is this.

**Background**
The application runs code in the background. Most apps briefly experience this status before being suspended. However, a program requiring more execution time can stay in this condition for a while.

**Suspended**
No code is being executed even if the program is running in the background. Before the system converts them to this mode automatically, apps are not informed. A paused program still has memory, but it is not actively running any code.

9. What is Deep Linking in iOS?
Deep Linking in mobile apps is the future frontier for exponentially increasing product and services sales. It is comparable to clickable links on web pages, except, in this case, it directs consumers to certain pages within mobile apps. Instead of just opening a mobile app and navigating to a specific page inside it, this technology instantaneously integrates mobile applications, giving users direct access to services.
The current state of mobile app technology prevents smooth navigation and interaction between several apps. Deep linking provides a solution by making it easier for users to find certain landing pages within the app.

10. What is Grand Central Dispatch (GCD)?
GCD optimizes software for multicore computers. It aids in concurrent code execution by delegating thread pool management from the developer to the OS.
in iOS, GCD is used for:
 - Making an app more responsive by carrying out complicated activities in the background.
 - Offering a better concurrency model than the typical locks and threads to prevent concurrency errors.

11. What is Automatic Reference Counting?
Automatic Reference Counting is a compile-time memory management technique. It guarantees objects are kept in memory only as long as they are required in object-oriented software development or are removed otherwise.

12. What is Cocoa Touch?
To create iOS applications, Apple created the Cocoa Touch framework. Classes in Cocoa Touch that begin with "NS" or "UI". Cocoa is a prerequisite for running applications on the iPhone. Think of cocoa or any framework as a bridging mechanism between a device and a programming language.

13. What is the difference between a thread and a process?
**Process**
A process is a program in execution or a dynamic instance of a program waiting in the queue or using the CPU. Many components make up a process, as follows:
 - Process ID
 - Memory Sections (stack, heap, text, code sections)
 - Process State
 - Program Counter
 - List of Open Apps

**Thread**
The fundamental components of CPU usage is a thread. The process itself is a component of a thread. There might be more than one thread in a process. Crucial parts that make up a thread include:
 - Thread ID
 - Program Counter
 - Register Set
 - Stack

 14. What are Design Patterns?
 In essence, design patterns are repaeatable code solutions that may be applied repeatedly to address typical software issues. Using design patterns in your projects will result in more modular, more scalable, and optimized software. You'll better comprehend other people's code since you'll be able to recognize the design pattern right away.

Design patterns do not serve as guidelines for creating better software, as design patterns and best practices are totally unline one another. Moreover, they are not intended to provide instructions on how to approach challenges. Rather, they merely serve as documentation of observed usual responses to typical engineering and architectural concepts. Common design patterns include Facade, Decorator, Factory Method, Singleton etc.

15. How well do you understand **assign** and **retain** keywords?
Assign: This keyword enables us to construct a reference from one object to another without increasing the source's retain count. The retain count keeps track of how many objects are clinging to one another. The value is immediately assigned to the instance variable.

Retain: It is the opposite of the keyword assign. It establishes a reference between two objects, but it also raises the source's retain count.

16. How is Bundle ID different from APP ID?
Bundle IDs serve as the applications' exclusive IDs within the Apple ecosystem. The result? No two applications can share the same identification. You can use the bundle ID to identify app upgrades.

App ID string on the other hand, identifies any apps from the same development team. The string comprises of two segments: the Team ID and the Bundle ID. These segments are separated by a period (.). While developers provide Bundle IDs to identify a single program or a group of apps, Apple provides Team IDs to identify a certain development team.

17. What is the Singleton Design Pattern?
Singleton is an object construction design pattern. It comes under the "creative" design patterns. It allows us to have one and only one instance of a class. Singleton objects are typically used to give your application configuration options or a global environment.

18. What are the features of Swift Programming Language?
Some features of the Swift programming Language includes:
 - Simple to Understand: Swift reads similarly to English, making it simple for newcomers to learn.
 - Scalable: Swift is one of the most scalable programming languages and can extend features to both iOS and OSX platforms.
 - Easy to Maintain: As an IDE, XCode checks our code for problems before building the app, making it quick and easy to manage.
 - Quick: Swift is statically typed, making it faster than other programming languages.
 - Improved Memory Use: Swift's memory management is automated.

 19. What is a Facade Design Pattern?
 Face Pattern makes a system easier to use by disguising its complexity. Under a structural design pattern, it belongs. In this architecture, client programs can access the system, but it hides how it functions by giving clients a mroe user-friendly interface.
 In this approach, a sing class (FACADE) is constructed and contains user-defined functions as well as delegates that call other classes belonging to the system. As a result, the client code just communicates with Facade and not the underlying system.

 20. Which framework will you leverage to develop the application interface for iOS?
 UIKit is a Framework specifically designed for iOS development. This framework lets developers design an application's graphical infrastructure and user interface. It comprises the following:
  - User interface
  - Event handling
  - App Structure
  - Graphics, printing, and drawing

21. What is MVC?
The main MVC principle is the division of a program into three parts:
**Model**:
Data shape and business logic are referred to as models, which serve the database blueprint. The model maintains application data and accesses and stores the object model state in a database.
It updates the data and reacts to user requests for data reading. In this case, the Model communicate with the database to receive or publish data. Moreover, it takes requests linked to the database, processes them, and then returns the data to the user via the browser.

**Controller**:
The controller controls the View-Model interactions. What happens if a user wants to ask for data and receive a response? They would require the right business logic - an algorithm that accepts a user request, verifies it, or forwards it to another component. Then, the algorithm delivers the client response.

**View**:
The view is the user interface and presentation that gives end-users access to the application's resources and lets them send requests to the application's server or backend. Normally, the user can use a web browser or a mobile app to send the query to get certain resources, such as a specific web page. You can write the view entirely in HTML or with tools and frameworks like React, Vue, etc.

22. Can you explain Spritekit and SceneKit frameworks?
**SpriteKit**: This framework enables game developers to quickly and easily create 2D animated objects. It lets them create text, videos, images, shapes, and particles in two dimensions.

**SceneKit**: This is an iOS framework for creating 3D graphics. iOS game developers can use this framework to produce appealing 3D animated effects and scenes for iOS game applications.

23. What are the different pattern matching techniques in Swift?
In Swift, pattern matching is a powerful feature that can be used to match values against a set of patterns, including ranges, optionals, tuples, and enums. With pattern matching, we can write more concise and expressive code that is easier to read and maintain. It is commonly used in control flow statements such as *switch* and *if* statements, but it can also be used in other contexts such as function parameters and variable binding.
There are few pattern matching techniques in Swift, examples of such are shown, such as:
 - Tuple patterns
 - Type-casting patterns
 - Wildcard patterns
 - Optional patterns
 - Enumeration case patterns
 - Expression patterns