# android-interview-questions
A collection of interview questions I've seen over the years :)

• What is method overloading and overriding?

• What is the difference between abstract classes and interfaces?

• What happens if multiple interfaces have, the same methods?

• If multiple interfaces contain default business logic and a class inherits all of them, what problems can arise?

• What can replace multiple inheritance?

• What is serialization when transferring data between activities?

• The Serializable interface is empty- how does it work?

• What is reified in Kotlin?

• What concurrency utilities exist in Android?

• What is a race condition?

• can we use Mutex in coroutines?

• Why can't we use synchronized in coroutines?

• What is a coroutine?

• How do we start coroutines?

• If we start a coroutine with launch and spawn child coroutines inside it, what happens if one crashes?

• What is the difference in error handling between launch and async?

• Can we call coroutines from Java code?

• What does a suspend function become when used in Java?

• If we have a long-running task (e.g. downloading a file) and the user leaves the screen, how do we ensure the task
continues?

• what is the "when" keyword used for? What java construct does it replace?

• how can you invoke a "suspend" function in kotlin? What are some features of a suspend function?

• what are visibility modifiers in kotlin?

• what do you understand by the terms of "polymorphism" and "inheritance", can you give examples of when you might use them?

• how would you integrate jetpack compose into an existing xml app?

• Hot vs cold flow (compare them)

• Recomposition what is it and how to count it

• Imagine a scenario where you created a room db with an ID , username and email, and all of those are a string, but you needed to change the ID to an int, how can you do it? (after the app with the old schema was published and downloaded by many users)

• What is a coroutine

• What is a coroutine context

• Compare State flow and shared flow

• Side effect in Compose (what is it?)

• Build variant vs built flavour

• How to cancel a coroutine, what to do if a coroutine still runs after cancellation

• What is a memory leak, how to detect it

• Koin vs Hilt, what is the main difference

• MVVM vs MVP (compare how both operate), do you know any other architecture patterns

• What is a coroutine scope, what scopes do you know

• What is a view model responsible for in MVVM

• What is characteristic for view model scope

• How to secure an android app

• What is a data class and what differences it from a normal class

• How to handle saving data between recompositions and screen rotations in compose

• What is dependency injection, what libraries are popular for DI

• What is linting, what linting tools do you know

• What are your favourite features in kotlin

• How to secure an app from decompilation

• How to ensure your unit tests are good, what should we unit test

• How to ensure the code you've written cannot be "better"

• How would you store sensitive user data in your local app database (assuming you have to)

• How to ensure a composable is stable

• How can you add a description that will be read by the TalkBack feature for a Button in Compose?

• How would you check whether a library you're using has used an outdated version of another library? (if you cannot find the source code on Github nor open the lib in android studio)

• Why cant a Kotlin library Module depend on an Android Library Module?

• Explain the use-case of let, run, with, also, apply in Kotlin

• How does one create a singleton in kotlin? Is your implementation thread safe? (can't use any external libraries)

• What is Back Pressure in RxJava? How can one deal with back pressure?

• How do you ensure that the data classes (stored in a library that you only have read-access to) are included in the release build?

• Can a fragment exist (in memory and/or on screen) without a parent activity? 

• Is there a difference between lateinit and lazy in kotlin? if so, explain it

• what's crossline and inline?

• how does android secure application data from other apps?

• Explain the meaning of "Restartable", "Skippable" and "Stable" in compose development, what may passing unstable parameters to a composable cause?

• what is an ANR, how many seconds need to pass (ANR time) before the app throws an ANR?

• can you install 2 (or more) applications, with the same package, on the same device?

• What is Doze Mode and how does it affect background tasks and services?

• Why were data classes created? were they a thing in java as well? what functions do data class offer that normal classes do not?

• What is a memory leak, show me an example of a memory leak and how can you detect / fix them?

• Can you compare R8 and Proguard? why do we need them in the first place?

• Is it possible for an activity to run onDestroy() without running onPause() or onStop() first? If so give an example

• what is the difference between const val and val?

• If kotlin introduces null-safety, how did apps handle nullability in java? does null-safety in kotlin mean you can never get a NPE?

