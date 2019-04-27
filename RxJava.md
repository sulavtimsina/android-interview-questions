1. What is RxJava?
RxJava is a Java VM implementation of ReactiveX (Reactive Extensions): a library for composing asynchronous and event-based programs by using observable sequences.

2. What is RxAndroid?
This module adds the minimum classes to RxJava that make writing reactive components in Android applications easy and hassle-free.

3. What is ReactiveX?
ReactiveX is a combination of the best ideas from the Observer pattern, the Iterator pattern, and functional programming.

4. How do you download RxJava and RxAndroid in Android Project?
In the app level build.gradle file add the following lines inside dependencies:
```groovy
implementation 'io.reactivex.rxjava2:rxandroid:2.1.1'
implementation 'io.reactivex.rxjava2:rxjava:2.2.8'
```
