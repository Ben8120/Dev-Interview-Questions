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