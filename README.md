# ReactiveProgrammingRxAndroidKotlin
Learning about Reactive Programming with RxAndroid and Kotlin on Pluralsight.

# Reactive vs Imperative

## Reactive
Reactive systems are responsive, when a user is in your app, they want the app to be responsive. 

Reactive systems are resilient, this directly impacts the previous point. If a component of your system fails and is not resilient, it will directly impact the responsiveness of your app. Resilient apps attempt to isolate components from each other as much as possible. 

Reactive systems are elastic, this means that even if the data stream suddenly has a large load of data or a user's input increases dramatically, the app will handle it gracefully. 

Reactive systems are message driven. The underlying mechanism of communication that enables all of this is an asynchronous message passing system. This is provided to us with the ReactiveX APIs. A message passing system is what allows our various components to remain decoupled and independent from one another. It is what gives us the control to maintain an elastic app by monitoring the data load. The decoupling allows us to compartmentalize functionality, which in trun allows our apps to be responsive and resilient. 

Functional Programming
- Stateless: instead of keeping track of the state of data with member variables and additional objects, we simply chain functions together and manipulate data.
- Functions as first-class objects: ReactiveX allows us to operate on data streams with first-class functions. First-class functions can be treated just like a variable. 

Declarative -> Tell the computer what you want and let the system take care of it.

These are examples of asynchronous messaging systems. 
<img width="474" alt="image" src="https://user-images.githubusercontent.com/66931789/185505520-1dc155de-a3c7-4e6b-bec6-d8f88ec7500b.png">

RxJava and RxAndroid permit the same event-driven programming model as Otto, but they're more capable and more better control of threading. 

Kotlin is the perfect language to take advantage of what RxJava has to offer. 
It supports Functional tools, lambdas, it's concise. 










