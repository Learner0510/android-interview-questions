# 📚 Table of Contents

### 🎯 Kotlin Language Fundamentals
- [val vs var](#val-vs-var)
- [const keyword](#advantage-of-using-const)
- [String vs StringBuffer vs StringBuilder](#string-vs-stringbuffer-vs-stringbuilder)
- [== vs === (Equality Operators)](#-vs--equality-operators)
- [Elvis Operator (?:)](#elvis-operator-)
- [Labels](#labels)
- [Visibility Modifiers](#visibility-modifiers)
- [open keyword](#open-keyword)
- [internal visibility modifier](#internal-visibility-modifier)
- [open vs public](#open-vs-public)

### 🔧 Kotlin Advanced Features
- [inline function](#inline-function)
- [noinline keyword](#noinline-keyword)
- [crossinline keyword](#crossinline-keyword)
- [reified keyword](#reified-keyword)
- [lateinit vs lazy](#lateinit-vs-lazy)
- [Checking lateinit Initialization](#checking-lateinit-initialization)
- [Lazy Initialization](#lazy-initialization)
- [init block](#init-block)
- [Higher-Order Functions](#higher-order-functions)
- [Function That Returns a Function](#function-that-returns-a-function)
- [Lambdas](#lambdas)
- [Infix Notation](#infix-notation)
- [Delegates](#delegates)

### 🏗️ Kotlin Classes & Objects
- [Data Classes](#data-classes)
- [Sealed Classes](#sealed-classes)
- [Sealed Classes in Android](#sealed-classes-in-android)
- [Inline Classes](#inline-classes)
- [Companion Objects](#companion-objects)
- [Singleton Class](#singleton-class)
- [Extension Functions](#extension-functions)
- [Scope Functions (let, run, with, also, apply)](#scope-functions-let-run-with-also-apply)
- [apply Scope Function](#apply-scope-function)
- [let Scope Function](#let-scope-function)
- [apply vs with](#apply-vs-with)

### 📦 Collections & Data Operations
- [Collections](#collections)
- [List vs Array](#list-vs-array)
- [Removing Duplicates from an Array](#removing-duplicates-from-an-array)
- [associateBy](#associateby)
- [partition Filtering Function](#partition-filtering-function)

### ☕ Java Interoperability
- [@JvmStatic Annotation](#jvmstatic-annotation)
- [@JvmField Annotation](#jvmfield-annotation)
- [@JvmOverloads Annotation](#jvmoverloads-annotation)
- [Java Static Methods Equivalent](#java-static-methods-equivalent)

### 🌊 Kotlin Coroutines
- [What are Coroutines?](#coroutines)
- [Suspending vs Blocking](#suspending-vs-blocking)
- [launch vs async](#launch-vs-async)
- [Dispatchers](#dispatchers-in-kotlin-coroutines)
- [coroutineScope vs supervisorScope](#coroutinescope-vs-supervisorscope)
- [Coroutine Scope](#coroutine-scope)
- [Coroutine Context](#coroutine-context)
- [Coroutine Scopes in Android](#coroutine-scopes-in-android)
- [runBlocking](#runblocking-in-coroutines)
- [Structured Concurrency](#structured-concurrency)
- [withContext](#withcontext)
- [Thread.sleep() vs delay()](#threadsleep-vs-delay)
- [Coroutine Timeouts](#coroutine-timeouts)
- [Combining Coroutine Results](#combining-coroutine-results)
- [Job in Coroutines](#job-in-coroutines)
- [job.cancel() vs scope.cancel()](#jobcancel-vs-scopecancel)
- [Exception Handling in Coroutines](#exception-handling-in-coroutines)
- [Exception in Unawaited async](#exception-in-unawaited-async)
- [Debounce with Coroutines](#debounce-with-coroutines)
- [Coroutines in Series and Parallel](#coroutines-in-series-and-parallel)
- [yield in Coroutines](#yield-in-coroutines)
- [Callback to Coroutines](#callback-to-coroutines-in-kotlin)
- [Retrofit with Kotlin Coroutines](#retrofit-with-kotlin-coroutines)
- [Room Database with Kotlin Coroutines](#room-database-with-kotlin-coroutines)
- [Unit Testing with Coroutines](#unit-testing-viewmodel-with-kotlin-coroutines-and-livedata)

### 🌊 Kotlin Flow API
- [Flow Builder, Operator, Collector](#flow-builder-operator-collector)
- [flowOn, Dispatchers](#flowon-dispatchers)
- [Flow Operators](#operators)
- [Terminal Operators](#terminal-operators)
- [Cold Flow vs Hot Flow](#cold-flow-vs-hot-flow)
- [StateFlow and SharedFlow](#stateflow-sharedflow-callbackflow-channelflow)
- [stateIn vs shareIn](#statein-vs-sharein-in-flow)
- [flatMapConcat, flatMapMerge, flatMapLatest](#flatmapconcat-flatmapmerge-and-flatmaplatest)
- [collect vs collectLatest](#collect-vs-collectlatest)
- [Exception Handling in Flow](#exception-handling-in-flow)
- [Unit Testing with Flow](#unit-testing-with-flow)

### 📱 Android Development
- #### Core Concepts
- [Android App Lag](#android-app-lag)
- [Context in Android](#context-in-android)
- [Android Project Structure](#android-project-structure)
- [AndroidManifest.xml](#androidmanifestxml)
- [Application Class](#application-class)
- [Android Application Components](#android-application-components)
- #### UI Components: Activity & Fragment
- [Activity and its Lifecycle](#activity-and-its-lifecycle)
- [onCreate() vs onStart()](#oncreate-vs-onstart)
- [setContentView() in onCreate()](#why-do-we-need-to-call-setcontentview-in-oncreate-of-activity-class)
- [Activity Lifecycle - onDestroy without onPause/onStop](#when-only-ondestroy-is-called-for-an-activity-without-onpause-and-onstop)
- [Fragment and its Lifecycle](#fragment-and-its-lifecycle)
- [Fragment Default Constructor](#why-is-it-recommended-to-use-only-the-default-constructor-to-create-a-fragment)
- [Fragment vs Activity](#fragment-vs-activity)
- [When to Use a Fragment?](#when-to-use-a-fragment)
- [add() vs replace() Fragment Transactions](#add-vs-replace-fragment-transactions)
- [Purpose of addToBackStack()](#purpose-of-addtobackstack)
- [Communicating Between Two Fragments](#communicating-between-two-fragments)
- [Retained Fragment](#retained-fragment)
- [FragmentPagerAdapter vs FragmentStatePagerAdapter](#fragmentpageradapter-vs-fragmentstatepageradapter)
- #### UI Components: Views & Layouts
- [Views and ViewGroups](#views-and-viewgroups)
- [What is a View?](#what-is-a-view)
- [What are ViewGroups?](#what-are-viewgroups)
- [The View Tree](#the-view-tree)
- [Optimizing Layouts](#optimizing-layouts)
- [View.GONE vs View.INVISIBLE](#viewgone-vs-viewinvisible)
- [Creating a Custom View](#creating-a-custom-view)
- [RelativeLayout vs LinearLayout](#relativelayout-vs-linearlayout)
- [ConstraintLayout Optimization](#constraintlayout-optimization)
- [What is a Canvas?](#what-is-a-canvas)
- [What is a SurfaceView?](#what-is-a-surfaceview)
- #### UI Components: Lists
- [Displaying Lists of Content](#displaying-lists-of-content)
- [ListView vs RecyclerView](#listview-vs-recyclerview)
- [How RecyclerView Works](#how-recyclerview-works)
- [RecyclerView Components](#recyclerview-components)
- [RecyclerView.Adapter and RecyclerView.ViewHolder](#recyclerviewadapter-and-recyclerviewviewholder)
- [LayoutManager in RecyclerView](#layoutmanager-in-recyclerview)
- [RecyclerView Optimization](#recyclerview-optimization)
- [Optimizing Nested RecyclerView](#optimizing-nested-recyclerview)
- [Handling Multiple View Types](#handling-multiple-view-types)
- [DiffUtil](#diffutil)
- [RecyclerView.setHasFixedSize(true)](#recyclerviewsethasfixedsizetrue)
- [Updating a Specific Item](#updating-a-specific-item)
- [SnapHelper](#snaphelper)
- #### Component Communication & Navigation
- [Intents and Broadcasting](#intents-and-broadcasting)
- [launchMode in Android](#launchmode-in-android)
- [Bundle in Android](#bundle-in-android)
- #### Background Processing & Threading
- [Long-running Operations](#long-running-operations)
- [Parallel tasks with Kotlin Flow](#how-to-run-parallel-tasks-and-get-a-callback-when-all-are-complete---long-running-tasks-in-parallel-with-kotlin-flow)
- [ANR (Application Not Responding)](#what-is-anr-how-can-the-anr-be-prevented)
- [Services](#services)
- [Inter-process Communication](#inter-process-communication)
- [ThreadPool Advantages](#threadpool-advantages)
- [Daemon Threads vs. User Threads](#daemon-threads-vs-user-threads)
- [Looper, Handler, and HandlerThread](#explain-looper-handler-and-handlerthread)
- [Runnable vs. Thread](#can-you-explain-the-difference-between-a-runnable-and-a-thread-in-android)
- #### Data Saving & Persistence
- [Persisting Data in an Android App](#persisting-data-in-an-android-app)
- [Preserving Activity State](#how-would-you-preserve-the-activity-state-during-a-screen-rotation)
- [SharedPreferences - commit() vs apply()](#what-is-commit-and-apply-in-sharedpreferences)
- [Jetpack DataStore Preferences](#jetpack-datastore-preferences)
- [ORM (Object-Relational Mapping)](#what-is-orm-how-does-it-work)
- [Scoped Storage](#explain-scoped-storage-in-android)
- [Encrypting Data](#how-to-encrypt-data-in-android)
- #### Performance & Optimizations
- [Memory Optimizations](#memory-optimizations)
- [Improve Android App Performance](#improve-android-app-performance)
- [onTrimMemory() method](#what-is-the-ontrimmemory-method)
- [Identifying and fixing OutOfMemory issues](#how-to-identify-and-fix-outofmemory-issues)
- [Finding memory leaks](#how-do-you-find-memory-leaks-in-android-applications)
- [Battery Life Optimizations](#battery-life-optimizations)
- [Adaptive Battery using ML](#how-android-implements-adaptive-battery-using-ml)
- [Reducing battery usage](#how-to-reduce-battery-usage-in-an-android-application)
- [Doze and App Standby](#what-is-doze-what-about-app-standby)
- [What is overdraw?](#what-is-overdraw)
- #### Supporting Different Screens
- [Supporting Different Screen Sizes](#supporting-different-screen-sizes)
- [Supporting different resolutions](#how-do-you-support-different-types-of-resolutions)
- #### Permissions
- [Different protection levels](#what-are-the-different-protection-levels-in-permission)
- #### Native Programming
- [NDK and its use](#what-is-the-ndk-and-why-is-it-useful)
- [What is renderscript?](#what-is-renderscript)
- #### Android System Internals
- [Android Runtime (ART)](#what-is-android-runtime)
- [Dalvik, ART, JIT, and AOT](#dalvik-art-jit-and-aot-in-android)
- [Dalvik vs ART](#what-are-the-differences-between-dalvik-and-art)
- [Baseline Profiles](#baseline-profiles)
- [What is DEX?](#what-is-dex)
- [Multidex in Android](#what-is-multidex-in-android)
- [Manually calling Garbage Collector](#can-you-manually-call-the-garbage-collector)
- [App Starts: Hot, Warm & Cold](#android-app-starts-hot-warm--cold)
- #### Android Jetpack
- [What is Android Jetpack?](#what-is-android-jetpack-and-why-to-use-this)
- [What is a ViewModel?](#what-is-a-viewmodel-and-how-is-it-useful)
- [SharedViewModel in Android](#sharedviewmodel-in-android)
- [Android Architecture Components](#what-are-android-architecture-components)
- [StateFlow vs LiveData](#stateflow-vs-livedata-in-android-development)
- [What is LiveData?](#what-is-livedata-in-android)
- [LiveData vs ObservableField](#how-is-livedata-different-from-observablefield)
- [setValue vs postValue in LiveData](#what-is-the-difference-between-setvalue-and-postvalue-in-livedata)
- [Sharing ViewModel between Fragments](#how-do-you-share-viewmodel-between-fragments-in-android)
- [WorkManager and its use cases](#explain-workmanager-and-its-use-cases)
- [WorkManager minimum repeat interval](#minimum-repeat-interval-allowed-when-scheduling-a-periodicworkrequest-using-workmanager)
- [How WorkManager Guarantees Execution](#how-does-workmanager-guarantee-task-execution)
- [How ViewModel works internally](#how-does-viewmodel-work-internally)
- #### Miscellaneous
- [Push Notification Flow (FCM)](#android-push-notification-flow-using-fcm)

### 🌍 Cross-Platform
- [Kotlin Multiplatform](#kotlin-multiplatform)

### Memory Optimizations

#### Improve Android App Performance
To improve Android app performance, focus on these key areas:
* **Memory Management:** Minimize memory usage by avoiding memory leaks, using efficient data structures, and handling bitmaps carefully. Use the Android Studio Memory Profiler to identify issues.
* **CPU Optimization:** Reduce CPU usage by offloading long-running tasks from the main thread and optimizing your code. Use the Android Studio CPU Profiler to analyze performance.
* **Rendering Performance:** Ensure a smooth UI (60 fps) by avoiding **overdraw**, simplifying view hierarchies, and using **`ConstraintLayout`**.
* **Battery Efficiency:** Optimize for battery by using **`WorkManager`** for background tasks and batching network requests.

#### What is the `onTrimMemory()` method?
The **`onTrimMemory()`** method is a callback provided by the **`ComponentCallbacks2`** interface. The system calls this method to notify your app when memory is running low. Your app can then respond by releasing unnecessary resources to prevent the system from killing it. The method receives an integer argument that specifies the current memory pressure level, such as `TRIM_MEMORY_UI_HIDDEN` or `TRIM_MEMORY_RUNNING_CRITICAL`.

#### How to identify and fix OutOfMemory issues?
**`OutOfMemoryError`** (**`OOM`**) occurs when an app tries to allocate more memory than the available heap space. To fix this:
* **Use the Android Profiler:** Use the **Memory Profiler** to observe the app's memory usage in real time. Look for a consistently increasing memory graph, which indicates a memory leak.
* **Analyze Heap Dumps:** Capture a heap dump (`.hprof` file) from the Memory Profiler. Analyze it to see which objects are consuming the most memory.
* **Fix the Issues:**
    * **Bitmaps:** Load appropriately scaled bitmaps. Use libraries like **Glide** or **Coil**.
    * **Memory Leaks:** Fix leaks by not holding onto `Context` in long-lived objects. Use a **`ViewModel`**.
    * **Large Objects:** Use memory-efficient data structures.

#### How do you find memory leaks in Android applications?
* **Use the Android Studio Memory Profiler:** Monitor the memory usage graph. A continuously climbing graph indicates a leak.
* **Force Garbage Collection:** In the profiler, you can manually trigger garbage collection to see if memory is released as expected.
* **Capture and Analyze Heap Dumps:** Create a heap dump at a "clean" state and a "leaky" state. Compare the two dumps to find objects that should have been garbage collected. Tools like **LeakCanary** can automatically detect and report memory leaks.

### Battery Life Optimizations

#### How Android Implements Adaptive Battery Using ML?
Android's Adaptive Battery uses a machine learning model to predict which apps the user will use. Based on this prediction, it places apps into different buckets with varying levels of resource restrictions. This ensures that frequently used apps remain active, while less-used apps have their background activity limited to save battery.

#### How to reduce battery usage in an Android application?
* **Use `WorkManager` or `JobScheduler`:** For background tasks, these APIs schedule work to run at optimal times (e.g., when the device is charging) and batch tasks together.
* **Batch Network Requests:** Instead of many small network calls, batch them into fewer, larger requests to minimize radio usage.
* **Use Sensors Wisely:** Only register for sensor updates when needed, and unregister them when your app is in the background.
* **Minimize Wakelocks:** A **wakelock** prevents the device from sleeping. Use them sparingly and always release them as soon as possible.

#### What is Doze? What about App Standby?
* **Doze:** Introduced in Android 6.0, Doze is a power-saving mode that activates when a device is stationary, screen-off, and unplugged. It delays app background activity, network access, and jobs.
* **App Standby:** This feature restricts the background activity of apps that the user has not recently used. The system places an idle app in a standby bucket, where its background network access and jobs are restricted.

#### What is overdraw?
**Overdraw** describes the system drawing a pixel on the screen multiple times in a single frame. This happens when multiple UI elements overlap. Excessive overdraw wastes GPU resources and can lead to performance issues.

### Supporting Different Screen Sizes

#### How do you support different types of resolutions?
* **Density-Independent Pixels (dp):** Use `dp` units for specifying dimensions. The system scales `dp` values based on screen density.
* **Scaled Pixels (sp):** Use `sp` units for font sizes. `sp` scales with both screen density and the user's font size preference.
* **Resource Qualifiers:** Provide different resources for different screen configurations (e.g., `layout-sw600dp` for tablets, `drawable-xxxhdpi` for high-density screens).
* **`ConstraintLayout`:** Use **`ConstraintLayout`** to build responsive UIs that adapt to different screen sizes.
* **Vector Drawables:** Use vector graphics for icons. They are scalable and avoid the need for multiple image assets for different densities.

### Permissions

#### What are the different protection levels in permission?
* **`normal`:** For permissions with minimal privacy risk. Granted automatically by the system at install time (e.g., `INTERNET`).
* **`dangerous`:** For permissions that access sensitive data. The user must explicitly grant these permissions at runtime (e.g., `CAMERA`, `ACCESS_FINE_LOCATION`).
* **`signature`:** Only granted to apps signed with the same key as the app that declared the permission.
* **`signatureOrSystem`:** Granted to apps with the same signature or to system apps.

### Native Programming

#### What is the NDK and why is it useful?
The **Android Native Development Kit (NDK)** is a set of tools that allows you to use C and C++ code with Android. It's useful for:
* **Performance-Critical Code:** For tasks like games, physics simulations, or signal processing.
* **Code Reusability:** To reuse existing C/C++ libraries.
* **Platform-Specific APIs:** To access certain low-level APIs.

#### What is renderscript?
**RenderScript** was a framework for writing high-performance, data-parallel computations. It was mainly used for image processing. It has been **deprecated** in favor of using native C++ APIs with the NDK.

### Android System Internals

#### What is Android Runtime?
The **Android Runtime (ART)** is the managed runtime used by the Android OS. It's responsible for converting an app's bytecode into native machine code. ART replaced Dalvik in Android 5.0 and improves performance through **Ahead-of-Time (AOT)** compilation.

#### Dalvik, ART, JIT, and AOT in Android
* **Dalvik:** The original Android runtime. It used a **Just-in-Time (JIT)** compiler, which compiled app code into native code at runtime.
* **ART:** The current Android runtime. It uses **Ahead-of-Time (AOT)** compilation, which compiles app code into native code when the app is installed.
* **JIT:** **Just-in-Time** compilation (code is compiled at runtime).
* **AOT:** **Ahead-of-Time** compilation (code is compiled before it runs).

#### What are the differences between Dalvik and ART?
| Feature | Dalvik | ART |
| :--- | :--- | :--- |
| **Compilation** | JIT (Just-in-Time) | AOT (Ahead-of-Time) |
| **App Install** | Faster | Slower |
| **Runtime Performance** | Slower startup | Faster startup |
| **Battery Life** | Lower efficiency | Better efficiency |
| **Memory Footprint** | Smaller | Larger |

#### Baseline Profiles
**Baseline Profiles** are rules included in your app that specify which parts of the code are critical. **ART** uses these profiles to compile that critical code **AOT**, providing a balance between faster installation and optimized runtime performance.

#### What is DEX?
**DEX** stands for **Dalvik Executable**. It is a file format containing compiled code that runs on the Android platform. All the `.class` files in an app are compiled into one or more `.dex` files, which are then executed by ART.

#### What is Multidex in Android?
**Multidex** allows an Android app to exceed the 65,536 method limit of a single `.dex` file. When an app is too large, Multidex splits the app's code into multiple `.dex` files, which the system then loads at runtime.

#### Can you manually call the Garbage collector?
Yes, using `System.gc()`, but it's only a **suggestion** to the system, not a command. It is generally considered bad practice to call it explicitly, as the Android runtime's garbage collector is highly optimized.

#### Android App Starts: Hot, Warm & Cold
* **Cold Start:** The app is launched for the first time since boot or since the system killed it. The process is created from scratch. This is the slowest start.
* **Warm Start:** The app process is already running, but the activity is not in memory. The system reuses the process but recreates the activity. Faster than a cold start.
* **Hot Start:** The app's process and activity are still in memory. The system simply brings the activity to the foreground. This is the fastest start.

### Android Jetpack

#### What is Android Jetpack and why to use this?
**Android Jetpack** is a collection of libraries, tools, and guidance to help developers build high-quality Android apps.
**Why use it?**
* **Best Practices:** Components are designed to follow modern best practices.
* **Less Boilerplate:** Components like **`ViewModel`** and **`LiveData`** reduce boilerplate code.
* **Compatibility:** Jetpack libraries are backwards-compatible.
* **Improved App Stability:** Components like **`WorkManager`** and **`Lifecycle`** simplify complex tasks.

#### What is a ViewModel and how is it useful?
A **`ViewModel`** is a **lifecycle-aware component** designed to store and manage UI-related data. It survives configuration changes, such as screen rotations. This is useful because:
* It prevents data loss on screen rotation.
* It separates UI logic from data handling.
* It simplifies testing.

#### SharedViewModel in Android
A **`SharedViewModel`** is a **`ViewModel`** that is scoped to an `Activity` and shared between multiple `Fragments` within that `Activity`. It's a clean way for fragments to communicate with each other and share data.

#### What are Android Architecture Components?
**Android Architecture Components** are a set of libraries (part of Jetpack) designed to help build robust, testable, and maintainable apps. The main components are `LiveData`, `ViewModel`, `Room`, `Lifecycle`, and `WorkManager`.

#### StateFlow vs LiveData in Android Development
| Feature | `StateFlow` | `LiveData` |
| :--- | :--- | :--- |
| **Concurrency** | Built on Kotlin Coroutines, has full concurrency support. | Main thread-aware, but not fully concurrent. |
| **Lifecycle** | Not lifecycle-aware by default. Needs `repeatOnLifecycle`. | Is lifecycle-aware by default. |
| **Initial Value** | Requires an initial value. | Does not require an initial value. |
| **Use Case** | Ideal for a reactive UI and complex data streams. | Good for simple UI state and data holding. |

#### What is LiveData in Android?
**`LiveData`** is a **lifecycle-aware observable data holder**. It holds a value and notifies observers when the data changes, but only sends updates to observers that are in an active lifecycle state (e.g., `STARTED` or `RESUMED`).

#### How is LiveData different from ObservableField?
* **`LiveData`** is lifecycle-aware and automatically manages subscriptions.
* **`ObservableField`** is not lifecycle-aware. You must manually manage listeners to avoid memory leaks. `LiveData` is the modern and recommended approach.

#### What is the difference between setValue and postValue in LiveData?
* **`setValue()`:** Updates the `LiveData` value **synchronously** on the **main thread**.
* **`postValue()`:** Updates the `LiveData` value **asynchronously** from a background thread.

#### How do you share ViewModel between Fragments in Android?
To share a **`ViewModel`** between fragments, scope the `ViewModel` to their shared `Activity`. Instead of using `ViewModelProvider(this)`, create it with `ViewModelProvider(requireActivity())`. Both fragments will then get the same instance.

#### Explain WorkManager and its use cases.
**`WorkManager`** is a library for managing deferrable background tasks that are guaranteed to run, even if the app exits or the device restarts.
* **Use Cases:** Sending logs, periodically syncing data, uploading images.
* **Key Features:** Guaranteed execution, support for constraints (e.g., requires network, requires charging), and both one-time & periodic work.

#### Minimum repeat interval allowed when scheduling a PeriodicWorkRequest using WorkManager
The minimum repeat interval for a **`PeriodicWorkRequest`** is **15 minutes**. Any value less than this will be automatically adjusted up to 15 minutes.

#### How Does WorkManager Guarantee Task Execution?
**`WorkManager`** guarantees execution by using a persistent, internal database to store all work requests. If the device reboots or the app is killed, `WorkManager` reads its database upon restart and reschedules any pending tasks.

#### How does ViewModel work internally?
When you request a `ViewModel`, a `ViewModelProvider` checks a `ViewModelStore` associated with the `Activity` or `Fragment`. The `ViewModelStore` is a simple map that holds `ViewModel` objects. When a configuration change occurs, the **`ViewModelStore` is retained**, and the new UI component instance gets the same `ViewModel` from it. When the UI component is finally destroyed, its `onCleared()` method is called.

### Long-running Operations

#### How to run parallel tasks and get a callback when all are complete - Long-running tasks in parallel with Kotlin Flow
To run parallel tasks and get a callback when all are complete in Kotlin Flow, you can use the **`zip`** or **`merge`** operators. The **`zip`** operator combines the latest values from multiple flows and emits a single value when all flows have emitted a value. This is useful when you need to wait for all tasks to complete before processing their results together. Conversely, the **`merge`** operator combines multiple flows into a single flow, emitting values as they become available from any of the source flows. To get a callback after all tasks are done, you can use **`merge`** with a **`collect`** block, and then use a counter or a similar mechanism to determine when all expected items have been received. For more complex scenarios, you can use **`coroutineScope`** with multiple **`async`** blocks to start parallel tasks and then **`awaitAll()`** to suspend until all tasks are finished, at which point you can execute your callback logic.

#### What is ANR? How can the ANR be prevented?
**ANR** stands for **Application Not Responding**. An ANR occurs when an Android app's main thread (UI thread) is blocked for too long, typically around 5 seconds for user input or 10 seconds for broadcast receivers. This makes the app appear frozen, leading to a system dialog that gives the user the option to either wait or close the app.

To prevent ANRs:
* **Offload long-running operations:** Move any time-consuming tasks, such as network calls, database queries, or complex calculations, off the main thread using Kotlin coroutines, `HandlerThread`, or other threading models.
* **Use appropriate threading models:** Utilize Kotlin Coroutines with **`Dispatchers.IO`** or **`Dispatchers.Default`** for background work.
* **Optimize UI updates:** Ensure that UI updates are as fast as possible. Avoid complex view hierarchies and excessive drawing operations.
* **Avoid synchronous calls on the main thread:** Never perform I/O operations directly on the main thread.
* **Profile your app:** Use Android Studio's profiler to identify performance bottlenecks.

#### ThreadPool Advantages
A **ThreadPool** is a managed collection of worker threads used to execute a queue of tasks. The main advantages are:
* **Improved Performance:** A thread pool reuses existing threads, significantly reducing the overhead of creating and destroying threads.
* **Resource Management:** It limits the number of threads running concurrently, preventing the system from being overwhelmed.
* **Concurrency Control:** It provides a mechanism to manage and schedule a large number of tasks efficiently.
* **Enhanced Stability:** It prevents the application from crashing due to an excessive number of threads exhausting system resources.

#### Daemon Threads vs. User Threads
* **User Threads:** These are foreground threads. The Java Virtual Machine (JVM) will not exit until all user threads have finished their execution.
* **Daemon Threads:** These are background threads. The JVM will exit automatically once all user threads have completed, regardless of whether any daemon threads are still running. They are typically used for non-critical tasks like garbage collection. You can set a thread as a daemon thread using **`thread.setDaemon(true)`**.

#### Explain Looper, Handler, and HandlerThread.
* **`Looper`:** A **`Looper`** is a class that manages a message queue for a thread. The `Looper` "loops" forever, pulling messages from its queue and dispatching them to the appropriate **`Handler`**.
* **`Handler`:** A **`Handler`** allows you to send messages (`Message` objects) or `Runnable` objects to a thread's message queue. It is the primary mechanism for communicating between background threads and the main thread for UI updates.
* **`HandlerThread`:** A **`HandlerThread`** is a convenience class that simplifies creating a background thread that has its own `Looper` and message queue.

#### Garbage Collection
**Garbage Collection** (**GC**) is an automatic memory management process in which the JVM reclaims memory occupied by objects that are no longer in use by the application. The garbage collector identifies "unreachable" objects and deallocates their memory. This prevents memory leaks and simplifies memory management for developers.

#### Memory Leak vs Out of Memory(OOM) Error
* **Memory Leak:** A **memory leak** occurs when an object that is no longer needed remains referenced, preventing the garbage collector from reclaiming its memory. Over time, these unreleased objects consume more and more memory.
* **Out of Memory (OOM) Error:** An **`OOM`** error occurs when the application attempts to allocate more memory than is available in the Java heap. This is often the **result of a severe memory leak** but can also be caused by allocating a single, very large object (e.g., a large bitmap). When an OOM error happens, the application crashes.

#### Can you explain the difference between a Runnable and a Thread in Android?
* **`Runnable`:** An interface that represents a task to be executed. It defines a single method, **`run()`**, which contains the code to be executed. A `Runnable` object doesn't create a new thread itself.
* **`Thread`:** A class that represents a single thread of execution. It can be started to perform its task and manages the thread lifecycle.

In short, a `Runnable` defines the "what," and a `Thread` defines the "how" of concurrency. It's generally preferred to use a `Runnable` with a **`ThreadPoolExecutor`** or a dedicated worker thread.

### Working With Multimedia Content

#### How do you handle bitmaps in Android as it takes too much memory?
Bitmaps can consume significant memory. To handle them effectively:
* **Load Scaled-Down Versions:** Instead of loading a full-resolution bitmap, load a smaller version that matches the size of the view it will be displayed in. Use **`BitmapFactory.Options`** with **`inSampleSize`**.
* **Use Caching:** Implement a caching strategy like a **`LruCache`** (memory cache) and a disk cache.
* **Recycle Bitmaps:** On older Android versions, call **`bitmap.recycle()`** when a bitmap is no longer needed. In newer versions, the garbage collector handles this more efficiently.
* **Use Libraries:** Leverage image loading libraries like **Glide**, **Picasso**, or **Coil**, which handle scaling, caching, and background loading automatically.

#### Tell about the Bitmap pool.
A **Bitmap pool** is a mechanism for reusing bitmap objects to reduce memory allocation and garbage collection overhead. Instead of creating a new **`Bitmap`** object every time, a bitmap pool keeps a collection of previously used `Bitmap` objects. When a new bitmap is required, the pool is checked for a suitable, reusable bitmap. This significantly reduces memory churn. Image loading libraries like **Glide** and **Coil** implement bitmap pooling internally.

### Data Saving & Persistence

#### Jetpack DataStore Preferences
**Jetpack DataStore Preferences** is a modern and robust replacement for **`SharedPreferences`**. It stores key-value pairs asynchronously and transactionally. Unlike `SharedPreferences`, `DataStore` is built on **Kotlin Coroutines** and **Flow**, making it safe to use on the main thread and ensuring data consistency.

#### Persisting Data in an Android App
* **File Storage:** Save data directly to internal or external storage.
* **SharedPreferences/DataStore:** Store primitive data in key-value pairs.
* **Databases (Room):** Use a relational database for structured data. **Room** is the recommended library.
* **Network/Cloud Storage:** Store data on a remote server.

#### What is ORM? How does it work?
**ORM** stands for **Object-Relational Mapping**. It is a programming technique that maps objects in your application to tables in a relational database. ORM libraries like **Room** provide a high-level API to interact with the database using objects and methods instead of writing raw SQL queries.

#### How would you preserve the Activity state during a screen rotation?
A screen rotation causes an `Activity` to be destroyed and recreated. To preserve its state:
* **`onSaveInstanceState()`:** The system calls this method before the `Activity` is destroyed. You can save small amounts of data into a `Bundle` here. When the `Activity` is recreated, the `Bundle` is passed to **`onCreate()`** where you can retrieve the data.
* **ViewModels:** A **`ViewModel`** is a lifecycle-aware component that survives configuration changes. It's the **recommended way** to store and manage UI-related data, as it is not destroyed during rotation.

#### What are different ways to store data in your Android app?
* **Shared Preferences/DataStore:** For primitive key-value data.
* **Internal Storage:** For storing private files accessible only by your app.
* **External Storage:** For storing public files. **Scoped Storage** has changed how this works since Android 10.
* **SQLite Database/Room:** For structured, relational data.
* **Network Connection:** For storing data on a remote server.

#### Explain Scoped Storage in Android.
**Scoped Storage**, introduced in Android 10, is a privacy feature that changes how apps access files on external storage. Instead of having broad access, an app can only access:
* **Its own app-specific directory.**
* **Shared media collections** (like Photos, Videos, Downloads) via the **`MediaStore`** API.
* **User-selected files** through the system file picker.

Scoped Storage improves user privacy by limiting an app's ability to access files it didn't create.

#### How to encrypt data in Android?
* **Jetpack Security Library:** This library provides a straightforward API for encrypting files and **`SharedPreferences`**. It is the recommended approach for most use cases.
* **Android Keystore System:** Securely stores cryptographic keys in a hardware-backed keystore, making them difficult to extract. You can use it to generate and manage keys for encryption.

#### What is commit() and apply() in SharedPreferences?
* **`commit()`:** Writes changes **synchronously**. It blocks the current thread until the write is complete. It should not be used on the main thread as it can cause an ANR.
* **`apply()`:** Writes changes **asynchronously**. It returns immediately and performs the write in the background. This is the **preferred method** for most use cases as it is non-blocking.

### Look and Feel

#### What is a Spannable?
A **`Spannable`** is an interface for text that can have markup objects ("spans") attached to it. These spans apply styling or behavior to specific parts of the text. Both the text and the spans are **mutable**.

#### What is a SpannableString?
A **`SpannableString`** is an implementation of `Spannable` where the text content is **immutable**, but the span information is **mutable**. You cannot change the characters, but you can add, remove, or modify styling spans. It's ideal for styling static text.

#### What are the best practices for using text in Android?
* **Use String Resources:** Always put text in **`strings.xml`** for localization and maintenance.
* **Use `Spannable` for Styling:** For styling parts of text, use `SpannableString`.
* **Avoid Hardcoding:** Never hardcode text directly in layouts or code.
* **Handle Text Overflow:** Use `ellipsize` and `maxLines` to handle long text gracefully.
* **Ensure Accessibility:** Add content descriptions for non-text elements.

#### How to implement Dark mode in any application?
1.  **Use a `DayNight` Theme:** Inherit your app's theme from a `DayNight` theme (e.g., `Theme.MaterialComponents.DayNight`).
2.  **Use DayNight Qualifiers:** Create a `res/values-night` directory and define alternative `colors.xml` and `themes.xml` files for the dark theme.
3.  **Use Theme Attributes:** Use theme attributes like **`?attr/colorPrimary`** and **`?attr/colorOnSurface`** in your layouts instead of hardcoded colors.
4.  **Allow User Control:** Give users an option to switch themes by calling **`AppCompatDelegate.setDefaultNightMode()`**.

### Views and ViewGroups

#### What is a View?
A `View` is the fundamental building block for all user interface components in an Android application. It's a simple rectangular box on the screen that draws something and can respond to user interaction. Examples include `Button`, `TextView`, and `ImageView`. The `android.view.View` class is the base class for all UI elements.

#### What are ViewGroups?
A `ViewGroup` is a special kind of `View` that acts as a container for other views and view groups. It's used to define the layout and arrangement of its child views. Think of it as an invisible container that organizes and groups UI elements. `ViewGroup` is the base class for all layout managers, such as `LinearLayout`, `FrameLayout`, and `ConstraintLayout`.

The main difference between a `View` and a `ViewGroup` is that a `View` is a single UI component, while a `ViewGroup` is a container that organizes and manages a collection of views. A `ViewGroup` is a subclass of `View`, but with additional responsibilities.

#### The View Tree
The view tree (or view hierarchy) is a tree-like data structure that represents the layout of your UI. The root of the tree is the top-level ViewGroup, which contains child views or other view groups, and so on.

You can optimize its depth by:

-   Using a flat layout structure 🏗️, especially with `ConstraintLayout`, to avoid deep nesting.
-   Using `<include>` and `<merge>` tags to reuse layout components and eliminate unnecessary ViewGroups.
-   Using `ViewStub` for views that are not always needed, as they don't add to the view hierarchy until they are inflated.

#### Optimizing Layouts
Optimizing layouts in Android is crucial for app performance, as a poorly designed layout can cause the app to lag or stutter. Key strategies include:

-   Using `ConstraintLayout` 🧘, which is highly efficient and can flatten the view hierarchy by creating complex UIs without nesting multiple ViewGroups.
-   Minimizing the view hierarchy depth by avoiding unnecessary nesting of layouts. A flatter tree is faster to measure and draw.
-   Using `<include>` and `<merge>` tags to reuse layouts and remove redundant ViewGroups. The `<merge>` tag is especially useful for reducing nesting when you're including one layout into another.
-   Using `ViewStub` for views that are rarely used, as it's a lightweight placeholder that only inflates the view when you explicitly make it visible.

#### View.GONE vs View.INVISIBLE
The key difference between these two visibility states is how they affect the layout:

-   **`View.INVISIBLE`**: The view is hidden, but it still takes up space in the layout. Other views will not move to fill its space.
-   **`View.GONE`**: The view is hidden and does not take up any space in the layout. The system treats it as if it's not in the view hierarchy, and other views will collapse to fill its space.

**Example:**
Imagine a `LinearLayout` with two buttons. If you set the first button's visibility to `View.INVISIBLE`, the second button will remain in its original position, with an empty space where the first button was. If you set the first button's visibility to `View.GONE`, the second button will slide over and take the first button's place.

#### Creating a Custom View
Yes, you can create a custom view by extending an existing `View` class (like `TextView` or `Button`) or the base `View` class itself. You must override the following methods:

-   **Constructors**: To allow the view to be instantiated from code or XML.
-   **`onMeasure()`**: To define the size of your custom view.
-   **`onDraw()`**: To draw the view's content using a `Canvas` object.
-   **`onTouchEvent()`**: To handle user interactions.

This allows you to create unique UI components with custom drawing and behavior.

#### RelativeLayout vs LinearLayout
| Feature | LinearLayout | RelativeLayout |
| :--- | :--- | :--- |
| **Arrangement** | Arranges views in a single row or column (either horizontal or vertical). | Arranges views based on their position relative to other views or the parent container. |
| **Simplicity** | Simpler and generally more performant for simple, linear arrangements. | More complex but offers greater flexibility in positioning views. |
| **Nesting** | Can lead to deep nesting for complex UIs, which hurts performance. | Can often flatten the view hierarchy by avoiding nesting. |
| **Ideal Use Case** | Simple lists, forms, or stacks of views. | Overlapping views or complex layouts where a view's position depends on another's. |

#### ConstraintLayout Optimization
`ConstraintLayout` is a powerful and flexible `ViewGroup` that is a strong choice for layout optimization because it can flatten the view hierarchy. It allows you to build complex and responsive UIs without the need for nested layouts. By using constraints to define the position of each view relative to other views or the parent, you can avoid the performance penalties of deep view trees. It also offers features like `Guidelines` and `Barriers` for easier alignment and grouping of views.

#### What is a Canvas?
A `Canvas` is a drawing surface in Android. It provides a set of methods for drawing on a bitmap or a view. When you override the `onDraw()` method of a custom view, the `Canvas` object is passed as an argument. You use the `Canvas` object's methods (e.g., `drawRect()`, `drawText()`, `drawBitmap()`) along with a `Paint` object to define what gets drawn on the screen.

#### What is a SurfaceView?
A `SurfaceView` is a special type of `View` that provides a dedicated drawing surface embedded in the view hierarchy. Unlike a regular `View` where all drawing happens on the main UI thread, a `SurfaceView` has its own separate thread for drawing. This makes it ideal for performance-intensive tasks like games, camera previews, or video playback, as the drawing operations won't block the main UI thread.

### Displaying Lists of Content

#### ListView vs RecyclerView
The `RecyclerView` is the modern and highly optimized successor to the `ListView`. The key differences are:

-   **Recycling**: `RecyclerView` reuses view holders, which dramatically improves performance by avoiding expensive `findViewById` calls and object creation during scrolling. `ListView` only recycles the views themselves.
-   **Layout Management**: `RecyclerView` decouples the layout from the list by using a `LayoutManager`, giving you more control over how items are positioned. `ListView` only supports a vertical list.
-   **Animations**: `RecyclerView` has built-in support for item animations when items are added, removed, or moved.
-   **Flexibility**: `RecyclerView` is a more flexible component for displaying various types of lists, grids, and staggered layouts.

#### How RecyclerView Works
`RecyclerView` improves performance over `ListView` by using a recycling pattern. Instead of creating a new view for every item in a large dataset, it creates a limited number of `ViewHolder` objects. When an item scrolls off the screen, its `ViewHolder` is returned to a pool. When a new item comes on-screen, a `ViewHolder` is pulled from the pool, re-bound with the new data, and displayed. This avoids the time-consuming process of inflating new layouts for every item.

#### RecyclerView Components
A `RecyclerView` has four essential components:

-   **`RecyclerView`**: The container view itself that displays the list.
-   **`RecyclerView.Adapter`**: Manages the data and creates/binds the `ViewHolders`.
-   **`RecyclerView.ViewHolder`**: A wrapper for a single list item view, holding references to its sub-views.
-   **`RecyclerView.LayoutManager`**: Defines how the items are laid out (e.g., as a vertical list or a grid).

#### RecyclerView.Adapter and RecyclerView.ViewHolder
-   **`RecyclerView.Adapter`**: Acts as the bridge between your data and the `RecyclerView`. It's responsible for:
    -   `onCreateViewHolder()`: Creating a new `ViewHolder` instance by inflating the item layout.
    -   `onBindViewHolder()`: Binding the data from your dataset to the views inside a `ViewHolder`.
    -   `getItemCount()`: Reporting the total number of items in the dataset.
-   **`RecyclerView.ViewHolder`**: A container for the view of a single list item. It holds references to the views within that item's layout. This is what allows for the efficient recycling of views, as it prevents repeated calls to `findViewById()`.

#### LayoutManager in RecyclerView
A `LayoutManager` is an abstract class that determines how items are arranged in the `RecyclerView`. It's a key part of `RecyclerView`'s flexibility. The three most common implementations are:

-   **`LinearLayoutManager`**: For a vertical or horizontal scrolling list.
-   **`GridLayoutManager`**: For a grid layout with a specified number of columns or rows.
-   **`StaggeredGridLayoutManager`**: For a grid where items have varying sizes, creating a staggered effect.

#### RecyclerView Optimization
Key ways to improve `RecyclerView` scrolling performance include:

-   Using `DiffUtil` to efficiently update the adapter when the data changes.
-   Calling `adapter.setHasStableIds(true)` if your data items have stable, unique IDs. This helps `RecyclerView` track items and prevent unnecessary re-binding.
-   Avoiding complex layouts and expensive drawing operations in the list items.
-   Ensuring that `onBindViewHolder()` is as lightweight as possible.
-   Using `RecyclerView.setHasFixedSize(true)` if the item size doesn't change.

#### Optimizing Nested RecyclerView
Nested `RecyclerViews` can cause performance issues. To optimize them:

-   Set `nestedScrollingEnabled` to `false` for the inner `RecyclerView` to prevent it from handling its own scrolling, letting the parent handle it.
-   Use a single, shared `RecyclerView.RecycledViewPool` for the inner adapters. This allows the inner lists to share `ViewHolders`, reducing memory overhead.

#### Handling Multiple View Types
You can handle multiple view types in a `RecyclerView` by overriding two methods in your adapter:

1.  **`getItemViewType(position: Int)`**: This method returns an integer representing the view type for an item at a specific position. You can use a condition (e.g., checking a data field) to return different integers for different view types.
2.  **`onCreateViewHolder(parent: ViewGroup, viewType: Int)`**: This method receives the `viewType` integer. You can use a `when` statement to inflate the correct layout and create the appropriate `ViewHolder` for each view type.

#### DiffUtil
`DiffUtil` is a utility class that calculates the difference between two lists and outputs a list of update operations that convert the old list into the new one. This is used to update a `RecyclerView`'s adapter. Instead of calling `notifyDataSetChanged()` (which is inefficient and re-binds all visible items), `DiffUtil` allows you to perform highly targeted and efficient updates, like adding, removing, or changing a single item. This provides smoother animations and better performance.

#### RecyclerView.setHasFixedSize(true)
Calling `recyclerView.setHasFixedSize(true)` is an optimization that tells the `RecyclerView` that its size will not change. This allows it to bypass a calculation step during measurement, making the process faster. You should only use this if the `RecyclerView`'s height and width are guaranteed to be the same regardless of its content. For example, if it's set to `match_parent` in both dimensions.

#### Updating a Specific Item
You can update a specific item in a `RecyclerView` by calling `adapter.notifyItemChanged(position)`. This is more efficient than `notifyDataSetChanged()` because it only re-binds the single item at the specified position. For an even more optimized approach, use `DiffUtil`, which will handle all the necessary insertions, removals, and changes for you.

#### SnapHelper
A `SnapHelper` is a utility class that provides snapping behavior to `RecyclerView` items, meaning that when the user scrolls, the `RecyclerView` will automatically stop with an item perfectly aligned to a specific point (e.g., the center of the screen). It's an abstract class, with common implementations being `LinearSnapHelper` (for lists) and `PagerSnapHelper` (for a `ViewPager`-like snapping behavior). It's great for creating carousels or image galleries.

### Dialogs and Toasts
- **Dialog**: A small, pop-up window that prompts the user for a response or provides information. It appears on top of the current Activity and pauses it until the dialog is dismissed. It's used for critical information or to get user input, like confirming an action.
- **Toast**: A small, temporary pop-up message that provides simple feedback to the user about an operation. It appears at the bottom of the screen, fades away automatically, and doesn't require user interaction. Toasts are for non-critical information that doesn't need to block the user.

| Feature | `Dialog` | `DialogFragment` |
| :--- | :--- | :--- |
| **Class** | An old-style class (`android.app.Dialog`) for creating dialogs. | A subclass of `Fragment` that manages a dialog. |
| **Lifecycle** | Has its own lifecycle, which is not tied to the Activity's lifecycle. This can cause issues like a `BadTokenException` if the Activity is destroyed. | Manages the dialog within the Fragment's lifecycle. It is the **recommended way** to create and manage dialogs because it handles state changes (like screen rotation) gracefully. |
| **State** | Prone to lifecycle-related issues and can leak memory. | Manages its own state, making it more robust and reliable. |

### Intents and Broadcasting
An **Intent** is a messaging object used to request an action from another app component. It's the primary mechanism for inter-component communication in Android. You can use it to start an Activity, a Service, or send a broadcast.

- An **Implicit Intent** doesn't name a specific component. Instead, it declares a general action to be performed (e.g., "view a webpage" or "take a photo"). The Android system finds a suitable component from all the installed apps to handle the action.

  **Example:**
  ```kotlin
  val intent = Intent(Intent.ACTION_VIEW, Uri.parse("https://www.google.com"))
  startActivity(intent)
  ```

- An **Explicit Intent** specifies the exact component to start by name. It's typically used to start a component within your own app.

  **Example:**
  ```kotlin
  val intent = Intent(this, SecondActivity::class.java)
  startActivity(intent)
  ```

A **BroadcastReceiver** is a component that listens for and responds to broadcast messages from other apps or the system. It doesn't have a UI and is typically used to react to events like a low battery, a change in connectivity, or a custom broadcast sent by your own app.

Broadcasts and Intents work together as a message-passing system. A component creates an Intent and wraps it in a broadcast. The system then sends this broadcast to all registered BroadcastReceivers. Each BroadcastReceiver that has declared a matching `IntentFilter` can receive the broadcast and perform an action in response.

**Example:**
```kotlin
// Sending a broadcast
val intent = Intent("com.example.MY_CUSTOM_ACTION")
sendBroadcast(intent)

// A BroadcastReceiver receiving it
class MyReceiver : BroadcastReceiver() {
    override fun onReceive(context: Context?, intent: Intent?) {
        if (intent?.action == "com.example.MY_CUSTOM_ACTION") {
            // Do something in response
        }
    }
}
```

A **PendingIntent** is a token that gives another application or component permission to execute an Intent on your application's behalf at a later time. It's often used for things like notifications, alarms, or app widgets, where an event needs to be triggered even if your app's process is not running. It acts as a wrapper around an Intent.

There are two main types of broadcasts:
1. **Normal Broadcasts**: These are asynchronous and can be received by any registered receiver. The system delivers them in an undefined order, and they cannot be cancelled.
2. **Ordered Broadcasts**: These are delivered to receivers one at a time, in a priority order. A receiver can modify the data in the broadcast or even abort it entirely, preventing it from being passed to lower-priority receivers.

### Services
A **Service** is an application component that can perform long-running operations in the background, without a user interface. Services are used for tasks like playing music, downloading files, or fetching data from the network. They are not tied to the lifecycle of an Activity.

The **Service Lifecycle** is a series of callback methods that track the state of a Service:
- `onCreate()`: Called when the service is first created.
- `onStartCommand()`: Called every time a client explicitly starts the service. This is where you put the service's main task.
- `onBind()`: Called when another component binds to the service.
- `onDestroy()`: Called when the service is no longer used and is being destroyed.

A Service runs on the main thread of the application by default. This is a common misconception. If you perform a long-running operation within a service, it will block the main thread. To avoid this, you must explicitly manage background operations using a separate thread, a Coroutine, or a WorkManager.

| Feature | `Service` | `IntentService` (Deprecated) |
| :--- | :--- | :--- |
| **Thread** | Runs on the main thread by default. You must handle threading yourself. | Creates a separate worker thread to handle all incoming intents. All requests are handled in a queue. |
| **Concurrency** | Can handle multiple requests concurrently if you manage threads. | Processes one intent at a time on its worker thread. |
| **Lifecycle** | Must be explicitly stopped (e.g., with `stopSelf()`). | Automatically stops itself after all intents in its queue have been processed. |

A **Foreground Service** is a Service that is considered by the system to be an active, user-facing process. It must display a notification to the user while it is running. This makes the service less likely to be killed by the system in low-memory situations.

A **JobScheduler** is an Android API that allows you to schedule background tasks in a battery-efficient way. It batches jobs from different applications to run at an opportune time, based on conditions like network availability or charging status.

**WorkManager** guarantees task execution by leveraging various APIs like `JobScheduler`. It manages a persistent queue of work and stores it in a local database. This means that even if the app process is killed or the device is rebooted, the work will be rescheduled and executed. It's the **recommended** solution for deferrable background work that needs to be guaranteed to run.

### Inter-process Communication
Two distinct Android apps can interact using:
- **Intents**: To start another app's activity or service.
- **Broadcasts**: For sending and receiving system-wide or custom messages.
- **Content Providers**: For sharing data between apps.
- **Bounded Services**: Using **AIDL** (Android Interface Definition Language) to allow a component from one app to bind to a service in another app and make remote procedure calls.

It is possible to run an Android app in multiple processes by using the `android:process` attribute in the `AndroidManifest.xml`. This is often used for isolating a long-running or memory-intensive service in its own process.

**AIDL (Android Interface Definition Language)** is a tool that allows you to define the programming interface that both the client and service agree upon for inter-process communication (IPC). It is used for creating a bounded service that can be accessed by other applications.

For background processing in Android, you can use:
- **WorkManager**: For tasks that need to be guaranteed to run. **Recommended for deferrable work.**
- **Coroutines**: For lightweight, asynchronous tasks.
- **Services**: For long-running background tasks.

A **ContentProvider** is a component that manages access to a structured set of data. It provides a standard interface for sharing data between applications, typically acting as a wrapper around a database to allow other apps to query, insert, update, or delete data in a secure way.

### 📱 Android Development

### Android App Lag
An Android app lags primarily due to blocking the main thread. The main thread (also called the UI thread) is responsible for handling user interactions, drawing the UI, and updating the screen. If this thread is blocked by a long-running operation, such as a complex calculation, a network request, or a database query, the app becomes unresponsive and appears to freeze or "lag."

**Example:**
If you fetch data from a server on the main thread, the app will freeze until the network request completes. This can be solved by moving the operation to a background thread using technologies like Coroutines or RxJava.

### Context in Android
Context is a handle to the Android system's resources and services. It provides access to application-specific resources, themes, and configuration. Think of it as a bridge between your application components and the Android system. It's essential for tasks like:

- Accessing resources (e.g., strings, layouts, drawables).
- Creating views and layouts.
- Starting new activities or services.
- Getting system services like a `LayoutInflater` or `WindowManager`.

**Example:**
When you need to get a string from your resources, you use `context.getString(R.string.my_string)`.

### Android Application Components
Android has four main application components, which are the building blocks of any app:

1.  **Activities:** Provide a screen with a UI that the user can interact with. Each activity represents a single screen with a specific task (e.g., a login screen or a settings screen).
2.  **Services:** Run in the background to perform long-running operations without a UI. Examples include playing music in the background or downloading a file.
3.  **Broadcast Receivers:** Listen for system-wide broadcasts or intents (e.g., low battery, incoming text message, or a photo being taken) and react to them.
4.  **Content Providers:** Manage a shared set of application data. They provide a standardized interface for sharing data between different applications.

### Android Project Structure
A typical Android project has a modular structure organized for clarity and build efficiency. The key directories are:

-   `app/src/main/java`: Contains your Kotlin or Java source code.
-   `app/src/main/res`: Contains all application resources like layouts (`layout/`), images (`drawable/`), string values (`values/`), and more.
-   `app/src/main/AndroidManifest.xml`: The manifest file, which describes the essential information about your app to the Android system.
-   `app/build.gradle`: The Gradle build script for your app module, where you define dependencies, build configurations, and other project settings.

### AndroidManifest.xml
The `AndroidManifest.xml` file is a crucial part of every Android app. It's the "ID card" for your application, providing the Android system with vital information. It declares:

-   The application's package name.
-   Its components (activities, services, etc.).
-   Required hardware features.
-   Permissions needed to run the app (e.g., `INTERNET` or `CAMERA`).
-   The application's icon and label.

Without a manifest, the system can't run your app's components.

### Application Class
The `Application` class is the base class for maintaining global application state. It's instantiated before any other component (like an Activity) when your application's process is started. It's a great place to perform one-time initialization for your entire application, like setting up a database or a dependency injection container. However, because it's a singleton, it should be used judiciously to avoid creating a God object. You can create your own custom `Application` class by extending `android.app.Application` and declaring it in the `AndroidManifest.xml`.

### Activity and its Lifecycle
An `Activity` represents a single screen in your app. It has a well-defined lifecycle managed by the Android system. The lifecycle consists of a series of callback methods that are called as the activity transitions through different states. The key states and their callbacks are:

-   `onCreate()`: The activity is being created. You set up the UI here.
-   `onStart()`: The activity is about to become visible.
-   `onResume()`: The activity is in the foreground and can be interacted with.
-   `onPause()`: Another activity is coming into the foreground, but this one is still partially visible.
-   `onStop()`: The activity is no longer visible to the user.
-   `onDestroy()`: The activity is being destroyed.

### onCreate() vs onStart()
| Callback | `onCreate()` | `onStart()` |
| :--- | :--- | :--- |
| **When Called** | When the activity is first created. It's called only once during the entire lifecycle of an activity instance. | When the activity is about to become visible to the user. It's called after `onCreate()` and every time the activity is brought to the foreground. |
| **Use Case** | Mandatory for initial setup, like calling `setContentView()`, initializing views, and binding data. | For tasks that need to run whenever the activity becomes visible, like starting animations or registering listeners. |

### onSaveInstanceState() and onRestoreInstanceState()
-   **`onSaveInstanceState()`**: This callback is invoked by the system to allow an activity to save its dynamic state (like the text in an `EditText` or the scroll position of a `RecyclerView`) as a `Bundle` object. This happens when the activity is killed by the system to reclaim resources (e.g., during a configuration change or low memory conditions).
-   **`onRestoreInstanceState()`**: This callback is invoked after `onStart()` if the activity is being recreated after being killed by the system. The `Bundle` saved in `onSaveInstanceState()` is passed to this method, allowing you to restore the activity's state.

**Example:**
```kotlin
override fun onSaveInstanceState(outState: Bundle) {
    super.onSaveInstanceState(outState)
    outState.putString("key_text", myEditText.text.toString())
}

override fun onRestoreInstanceState(savedInstanceState: Bundle) {
    super.onRestoreInstanceState(savedInstanceState)
    val myText = savedInstanceState.getString("key_text")
    myEditText.setText(myText)
}

### 📱 Android Development

### Android App Lag
An Android app lags primarily due to blocking the main thread. The main thread (also called the UI thread) is responsible for handling user interactions, drawing the UI, and updating the screen. If this thread is blocked by a long-running operation, such as a complex calculation, a network request, or a database query, the app becomes unresponsive and appears to freeze or "lag."

**Example:**
If you fetch data from a server on the main thread, the app will freeze until the network request completes. This can be solved by moving the operation to a background thread using technologies like Coroutines or RxJava.

### Context in Android
Context is a handle to the Android system's resources and services. It provides access to application-specific resources, themes, and configuration. Think of it as a bridge between your application components and the Android system. It's essential for tasks like:

- Accessing resources (e.g., strings, layouts, drawables).
- Creating views and layouts.
- Starting new activities or services.
- Getting system services like a `LayoutInflater` or `WindowManager`.

**Example:**
When you need to get a string from your resources, you use `context.getString(R.string.my_string)`.

### Android Application Components
Android has four main application components, which are the building blocks of any app:

1.  **Activities:** Provide a screen with a UI that the user can interact with. Each activity represents a single screen with a specific task (e.g., a login screen or a settings screen).
2.  **Services:** Run in the background to perform long-running operations without a UI. Examples include playing music in the background or downloading a file.
3.  **Broadcast Receivers:** Listen for system-wide broadcasts or intents (e.g., low battery, incoming text message, or a photo being taken) and react to them.
4.  **Content Providers:** Manage a shared set of application data. They provide a standardized interface for sharing data between different applications.

### Android Project Structure
A typical Android project has a modular structure organized for clarity and build efficiency. The key directories are:

-   `app/src/main/java`: Contains your Kotlin or Java source code.
-   `app/src/main/res`: Contains all application resources like layouts (`layout/`), images (`drawable/`), string values (`values/`), and more.
-   `app/src/main/AndroidManifest.xml`: The manifest file, which describes the essential information about your app to the Android system.
-   `app/build.gradle`: The Gradle build script for your app module, where you define dependencies, build configurations, and other project settings.

### AndroidManifest.xml
The `AndroidManifest.xml` file is a crucial part of every Android app. It's the "ID card" for your application, providing the Android system with vital information. It declares:

-   The application's package name.
-   Its components (activities, services, etc.).
-   Required hardware features.
-   Permissions needed to run the app (e.g., `INTERNET` or `CAMERA`).
-   The application's icon and label.

Without a manifest, the system can't run your app's components.

### Application Class
The `Application` class is the base class for maintaining global application state. It's instantiated before any other component (like an Activity) when your application's process is started. It's a great place to perform one-time initialization for your entire application, like setting up a database or a dependency injection container. However, because it's a singleton, it should be used judiciously to avoid creating a God object. You can create your own custom `Application` class by extending `android.app.Application` and declaring it in the `AndroidManifest.xml`.

### Activity and its Lifecycle
An `Activity` represents a single screen in your app. It has a well-defined lifecycle managed by the Android system. The lifecycle consists of a series of callback methods that are called as the activity transitions through different states. The key states and their callbacks are:

-   `onCreate()`: The activity is being created. You set up the UI here.
-   `onStart()`: The activity is about to become visible.
-   `onResume()`: The activity is in the foreground and can be interacted with.
-   `onPause()`: Another activity is coming into the foreground, but this one is still partially visible.
-   `onStop()`: The activity is no longer visible to the user.
-   `onDestroy()`: The activity is being destroyed.

### onCreate() vs onStart()
| Callback | `onCreate()` | `onStart()` |
| :--- | :--- | :--- |
| **When Called** | When the activity is first created. It's called only once during the entire lifecycle of an activity instance. | When the activity is about to become visible to the user. It's called after `onCreate()` and every time the activity is brought to the foreground. |
| **Use Case** | Mandatory for initial setup, like calling `setContentView()`, initializing views, and binding data. | For tasks that need to run whenever the activity becomes visible, like starting animations or registering listeners. |

### onSaveInstanceState() and onRestoreInstanceState()
-   **`onSaveInstanceState()`**: This callback is invoked by the system to allow an activity to save its dynamic state (like the text in an `EditText` or the scroll position of a `RecyclerView`) as a `Bundle` object. This happens when the activity is killed by the system to reclaim resources (e.g., during a configuration change or low memory conditions).
-   **`onRestoreInstanceState()`**: This callback is invoked after `onStart()` if the activity is being recreated after being killed by the system. The `Bundle` saved in `onSaveInstanceState()` is passed to this method, allowing you to restore the activity's state.

**Example:**
```kotlin
override fun onSaveInstanceState(outState: Bundle) {
    super.onSaveInstanceState(outState)
    outState.putString("key_text", myEditText.text.toString())
}

override fun onRestoreInstanceState(savedInstanceState: Bundle) {
    super.onRestoreInstanceState(savedInstanceState)
    val myText = savedInstanceState.getString("key_text")
    myEditText.setText(myText)
}
```

### Fragment and its Lifecycle
A `Fragment` represents a reusable portion of a user interface within an `Activity`. A fragment's lifecycle is closely tied to its host activity's lifecycle, but it has its own set of callbacks. A fragment can have different states, such as added, attached, and detached. The main lifecycle methods include:

-   `onAttach()`: The fragment has been attached to its host activity.
-   `onCreate()`: The fragment is being created.
-   `onCreateView()`: The fragment's view is being created and inflated.
-   `onViewCreated()`: The view has been created, and you can now access views.
-   `onStart()`: The fragment is now visible.
-   `onResume()`: The fragment is in the foreground.
-   `onPause()`: The fragment is no longer in the foreground.
-   `onStop()`: The fragment is no longer visible.
-   `onDestroyView()`: The fragment's view is being destroyed.
-   `onDestroy()`: The fragment instance is being destroyed.
-   `onDetach()`: The fragment is being detached from its host activity.

### Fragment vs Activity
| Feature | Fragment | Activity |
| :--- | :--- | :--- |
| **Component Type** | A modular part of an Activity. | A standalone component that represents a single screen. |
| **Lifecycle** | Dependent on the host Activity's lifecycle. | Independent lifecycle managed by the Android system. |
| **View Hierarchy** | Has its own view hierarchy. | Has its own view hierarchy. |
| **Communication**| Communicates with other fragments or the host Activity. | Communicates with other activities via `Intent`. |
| **Reusability** | Highly reusable across multiple activities. | Not easily reusable; typically represents a unique screen. |

The relationship between a fragment and an activity is that a fragment must always be hosted within an activity. A single activity can host multiple fragments, and a fragment can be reused across different activities.

### When to Use a Fragment?
You should use a `Fragment` instead of an `Activity` in the following scenarios:

-   When you have UI components that need to be reused across different activities.
-   When you need to support multiple screen sizes and orientations (e.g., showing a list and details side-by-side on a tablet but separately on a phone).
-   When you are implementing a `ViewPager` or `BottomNavigationView` where multiple screens exist within a single activity.

**Example:** A fragment for a user profile can be used on a phone as a full-screen activity and on a tablet as a side panel next to a list of users.

### FragmentPagerAdapter vs FragmentStatePagerAdapter
The difference lies in how they manage fragments:

-   **`FragmentPagerAdapter`**: Keeps all fragments in memory. It only destroys the fragment's views when they are off-screen, but the fragment instance remains. This is more memory-intensive but faster for a small number of pages because the fragment doesn't need to be recreated.
-   **`FragmentStatePagerAdapter`**: Destroys the entire fragment instance (except for its saved state) when it's not visible to the user. This is more memory-efficient and is recommended for a large number of pages where not all pages will be in memory at once.

### add() vs replace() Fragment Transactions
-   **`add()`**: Adds a new fragment to the container. If another fragment is already there, it will be placed on top of the existing fragment. The previous fragment remains in the view hierarchy, but it's not visible. This is useful when you want to show a transparent fragment on top of another.
-   **`replace()`**: Removes any existing fragment from the container and replaces it with a new one. The old fragment's view is destroyed. This is the more common method for navigating between different fragments.

### Purpose of addToBackStack()
When you perform a fragment transaction, like `replace()`, the old fragment is removed. By calling `transaction.addToBackStack(null)`, you save that transaction to the activity's back stack. This means that when the user presses the back button, the transaction is reversed, and the previous fragment is brought back. Without `addToBackStack()`, pressing the back button would simply close the host activity.

### Communicating Between Two Fragments
The recommended way to communicate between fragments is through their shared host activity or view model.

1.  **Shared Host Activity**: A fragment can define an interface that the host activity must implement. The fragment calls a method on this interface, and the activity then passes the data to the other fragment.
2.  **Shared ViewModel**: This is the modern, recommended approach. The two fragments share a `ViewModel` that lives as long as the host activity. One fragment updates a live data object in the `ViewModel`, and the other fragment observes that data and reacts to changes.

### Retained Fragment
A retained fragment is a fragment that survives configuration changes (like a screen rotation). By default, a fragment is destroyed and recreated along with its host activity. However, if you call `setRetainInstance(true)` on a fragment, its instance will be kept and reattached to the new activity instance after the configuration change. This is useful for retaining state or a long-running background task, as it prevents the task from being cancelled and restarted.

**Example:** A fragment for a network download task could be retained to prevent the download from restarting every time the user rotates the screen.

### Bundle in Android
A `Bundle` is a key-value data structure used to pass data between Android components. It's a key part of saving and restoring the UI state. It is optimized to work with small amounts of data. `Bundle` can hold primitive types, Strings, and `Serializable` or `Parcelable` objects. The `Bundle` class is used in `Intents` for passing data and in lifecycle callbacks like `onSaveInstanceState()`.

**Example:**
```kotlin
val bundle = Bundle()
bundle.putString("user_name", "Alice")
bundle.putInt("user_age", 30)

val myIntent = Intent(this, MyActivity::class.java)
myIntent.putExtras(bundle)
startActivity(myIntent)
```

### why is it recommended to use only the default constructor to create a fragment
It's recommended to use a default (no-argument) constructor for a `Fragment` because the Android system can destroy and recreate fragments at any time (e.g., during a configuration change like a screen rotation). When the system recreates the fragment, it uses the default constructor. If you have a custom constructor with arguments, the system won't know how to recreate the fragment, which can lead to crashes. To pass data to a fragment, you should use the arguments `Bundle` and the `newInstance()` static factory method pattern.

**Example (Incorrect):**
```kotlin
class MyFragment(val someData: String) : Fragment() // Don't do this!
```

**Example (Correct):**
```kotlin
class MyFragment : Fragment() {
    companion object {
        fun newInstance(someData: String): MyFragment {
            val args = Bundle()
            args.putString("key_data", someData)
            val fragment = MyFragment()
            fragment.arguments = args
            return fragment
        }
    }
}
```

### why do we need to call setcontentview in oncreate of activity class
You need to call `setContentView()` in the `onCreate()` method because this is the first and only time you can inflate the activity's layout from XML and bind it to the activity. The `onCreate()` method is where the initial setup of the activity takes place. It is a mandatory step to display a UI on the screen.

**Example:**
```kotlin
override fun onCreate(savedInstanceState: Bundle?) {
    super.onCreate(savedInstanceState)
    setContentView(R.layout.activity_main) // This must be called here
    // Now you can find views using findViewById
    val button = findViewById<Button>(R.id.my_button)
}
```

### when only ondestroy is called for an activity without onpause and onstop
An `onDestroy()` callback is called without `onPause()` and `onStop()` only when the `Activity` instance is an orphan and the system has to reclaim the memory from the process that contains the `Activity` instance. The `onPause()` and `onStop()` methods will not be called when `finish()` is called from within the `onCreate()` method of the `Activity`. This happens, for example, if a condition inside `onCreate()` fails, and you immediately call `finish()` to close the activity.

### launchMode in Android
`launchMode` is an attribute defined in the `AndroidManifest.xml` for an activity that specifies how the activity should be launched into its task stack. There are four launch modes:

-   **`standard`** (default): Creates a new instance of the activity every time it's launched.
-   **`singleTop`**: If an instance of the activity already exists at the top of the stack, a new instance is not created; instead, the existing one receives the `onNewIntent()` call.
-   **`singleTask`**: The activity is launched as the root of a new task. If an instance already exists in another task, the system brings that task to the foreground and calls `onNewIntent()`.
-   **`singleInstance`**: Similar to `singleTask`, but the activity is the sole member of its task. No other activities can be launched into the same task.


---

# Kotlin Flow API

The Kotlin Flow API is a powerful library for handling asynchronous data streams. It's built on top of coroutines, providing a reactive programming paradigm that's both efficient and easy to reason about. A **`Flow`** represents a stream of asynchronously computed values, similar to an RxJava `Observable`, but it's cold by default.

---

## Flow Builder, Operator, Collector

The Flow API is built around three main components that represent the lifecycle of a data stream:

*   **Flow Builder**: This is how you create a `Flow`. Builders produce values that are emitted into the stream. The most common builder is `flow { ... }`.
    ```kotlin
    val myFlow = flow {
        // Emit values into the stream
        for (i in 1..3) {
            emit(i)
            delay(100) // Simulate a non-blocking delay
        }
    }
    ```
*   **Operators**: These are functions that transform or modify the data emitted by a `Flow`. They operate on the upstream `Flow` and return a new `Flow`. Operators are a key part of the declarative nature of the Flow API.
    ```kotlin
    myFlow.map { it * 2 } // Transforms each emitted value
          .filter { it > 2 } // Filters values based on a condition
    ```
*   **Collector**: This is the final step in the stream. A collector consumes the values emitted by the `Flow`. The most common collector is `collect()`, which is a terminal operator.
    ```kotlin
    coroutineScope.launch {
        myFlow.collect { value ->
            println("Received: $value")
        }
    }
    ```

---

## `flowOn`, Dispatchers

The **`flowOn`** operator is used to change the `Dispatcher` (the thread or thread pool) that the upstream `Flow` runs on. This is crucial for separating I/O-bound work (like network calls or database operations) from CPU-intensive or UI work.

*   The upstream `Flow` (the part before `flowOn`) will run on the specified dispatcher.
*   The downstream `Flow` (the part after `flowOn`) will continue to run on its original context.

```kotlin
fun getItems(): Flow<Item> = flow {
    // This part runs on Dispatchers.IO
    // Good for database or network calls
    emit(api.fetchItems())
}.flowOn(Dispatchers.IO)
 // The collector will run on the original context (e.g., Dispatchers.Main)
 .onEach { // This operator runs on the new context
     // ...
 }
```

`flowOn` is an essential tool for making sure your `Flow`s are non-blocking and efficient.

---

## Operators

| Operator              | Description                                                                                             | Example                                         |
| :-------------------- | :------------------------------------------------------------------------------------------------------ | :---------------------------------------------- |
| **`filter`**          | Excludes items from the stream that don't satisfy a predicate.                                          | `flowOf(1, 2, 3).filter { it % 2 == 0 }` (emits 2) |
| **`map`**             | Transforms each value in the stream into another value.                                                 | `flowOf(1, 2).map { it * 10 }` (emits 10, 20)     |
| **`zip`**             | Combines the values of two `Flow`s into a single stream. It waits for a new value from both `Flow`s before emitting a combined value. Useful for parallel network calls. | `flow1.zip(flow2) { a, b -> a + b }`            |
| **`flatMapConcat`**   | Processes items sequentially. It concatenates the streams created from each upstream item. A new inner stream will not start until the previous one completes. | `flowOf(1, 2).flatMapConcat { requestData(it) }` |
| **`retry`**           | Retries the `Flow` when an exception occurs, up to a specified number of times.                         | `myFlow.retry(3)`                               |
| **`debounce`**        | Suppresses values that are emitted too quickly. It emits a value only after a specified time has passed without a new emission. Great for instant search. | `events.debounce(300)`                          |
| **`distinctUntilChanged`** | Filters out consecutive identical values.                                                               | `flowOf("A", "A", "B", "A").distinctUntilChanged()` (emits "A", "B", "A") |
| **`flatMapLatest`**   | Processes items concurrently. When a new value arrives, it cancels the previous inner stream and starts a new one. | `flowOf(1, 2).flatMapLatest { requestData(it) }` |

---

## Terminal Operators

A **terminal operator** is a function that starts the collection of a `Flow`. When a terminal operator is called, the `Flow` is activated, and the builder and operators begin emitting and processing values. A `Flow` is **cold** and does nothing until a terminal operator is called.

Common terminal operators include:

*   **`collect()`**: Collects all values from the `Flow`.
*   **`first()`**: Returns the first value from the `Flow`.
*   **`toList()`**: Converts all values to a list.
*   **`single()`**: Collects and returns the single value from the `Flow` (throws an exception if there are zero or multiple values).
*   **`launchIn()`**: A non-suspending way to launch a collection in a given `CoroutineScope`.

---

## Cold Flow vs. Hot Flow

| Feature   | Cold Flow                                                                 | Hot Flow                      |
| :-------- | :------------------------------------------------------------------------ | :---------------------------- |
| **Start** | Starts emitting values only when a collector starts collecting.            | Starts emitting values immediately, regardless of collectors. |
| **State** | Each collector gets a new, independent stream of data from the beginning. | All collectors share the same stream of data. |
| **Example** | `flow { emit(...) }`                                                      | **`StateFlow`**, **`SharedFlow`** |

A **cold `Flow`** is like a blueprint for a water faucet—it doesn't start producing water until you turn it on. A **hot `Flow`** is like a running water hose—it's always producing water, and new collectors can tap into the stream at any point.

---

## StateFlow, SharedFlow, callbackFlow, channelFlow

*   **`StateFlow`**: A hot `Flow` that represents a state. It always holds and emits a single, latest value. It's a great replacement for `LiveData` in many scenarios, as it's lifecycle-aware and can be easily used with coroutines. It's primarily used to represent UI state.
*   **`SharedFlow`**: A highly configurable hot `Flow` that can broadcast values to multiple collectors. It's useful for event streams where multiple parts of your app need to react to the same event. You can configure its replay cache and buffer size to control how it behaves.
*   **`callbackFlow`**: A builder used to convert a callback-based API into a `Flow`. It provides a `ProducerScope` that allows you to emit values from a callback and then close the `Flow` when the callback stream is finished. This is crucial for interoperability with older APIs.
*   **`channelFlow`**: A more powerful version of `callbackFlow`. It allows for more complex emission patterns, including sending values to the underlying channel from multiple coroutines.

---

## Exception Handling in Flow

Exceptions in a `Flow` are handled with a **`catch`** operator. The `catch` operator intercepts an exception from the upstream `Flow` and can handle it, log it, or emit a new value.

```kotlin
myFlow
    .onEach { throw IOException("Network error") } // This will throw an exception
    .catch { e ->
        // This operator catches the exception
        println("Caught exception: ${e.message}")
        // You can also emit a new value to recover
        emit("Fallback value")
    }
    .collect()
```

The `catch` operator is **upstream-only**; it cannot catch exceptions from downstream operators.

---

## Unit Testing with Flow

Testing a `ViewModel` that uses `Flow` and `StateFlow` is straightforward with the `kotlinx-coroutines-test` library.

1.  Use `TestCoroutineDispatcher` to control the coroutine execution.
2.  Use `runBlockingTest` or `runTest` to execute the coroutine scope.
3.  Use the `collect` terminal operator on your `StateFlow` to check its emitted values.

```kotlin
class MyViewModelTest {
    @get:Rule
    val instantTaskExecutorRule = InstantTaskExecutorRule() // For LiveData

    @get:Rule
    val mainCoroutineRule = MainCoroutineRule() // Custom rule for TestCoroutineDispatcher

    @Test
    fun `test fetch data and state updates`() = mainCoroutineRule.runBlockingTest {
        // Given
        val viewModel = MyViewModel(mockRepository)
        // A list to collect the state changes
        val states = mutableListOf<MyState>()
        val job = launch { viewModel.myState.toList(states) }
        
        // When
        viewModel.fetchData()
        
        // Then
        // Check initial state, loading state, and success state
        Truth.assertThat(states).containsExactly(MyState.Loading, MyState.Success("Data"))
        job.cancel()
    }
}
```

---

## Android Push Notification Flow using FCM

The Android push notification flow using Firebase Cloud Messaging (FCM) involves a few key steps and components:

- **Client App Instance**: When an app is installed on an Android device, the FCM SDK automatically generates a unique registration token. This token identifies the app instance on that specific device. The app should send this token to your app server.

- **App Server**: Your app server or a third-party server creates the notification payload. This payload can contain a `notification` field for a standard message (title, body, icon) and a `data` field for custom key-value pairs. The server then sends a request to the FCM server using this payload and the device's registration token.

- **FCM Server**: The FCM server receives the request, processes it, and routes the message to the target device. It handles the complexities of message delivery, even if the device is offline or in a low-power state (Doze mode).

- **Device**: The Android device receives the message from FCM. The behavior upon reception depends on the app's state:

  - **App in the background**: If the payload contains a `notification` field, FCM displays the notification in the system tray. The app's `onMessageReceived` method is not called. The data payload is delivered to the app when the user taps the notification.

  - **App in the foreground**: The `onMessageReceived` method of your app's `FirebaseMessagingService` is called immediately. The app receives the message object, which contains both notification and data payloads, and can handle the notification programmatically.

The main advantage of FCM is that it provides a reliable, cross-platform way to send messages without needing a constant open connection from your app to your server, which saves battery and resources.

---

## What is an inline function in Kotlin?

An inline function in Kotlin is a function that the compiler replaces with the actual function body at the call site. This is a form of code substitution that happens during compilation, not runtime.

The primary purpose of using inline functions is to reduce the overhead of lambda expressions. When a function takes a lambda as a parameter, the lambda is an object that gets created and allocated in memory. By inlining the function, the compiler avoids creating this object, which can improve performance, especially in loops or frequently called functions.

**Example:**

```kotlin
// A regular function with a lambda
fun calculate(a: Int, b: Int, operation: (Int, Int) -> Int): Int {
    return operation(a, b)
}

// An inline function
inline fun calculateInline(a: Int, b: Int, operation: (Int, Int) -> Int): Int {
    return operation(a, b)
}

// The 'calculateInline' function call
// will be replaced by the compiler with:
// return a + b
```

---

## What is the advantage of using const in Kotlin?

The primary advantage of using `const` in Kotlin is that it creates a compile-time constant. The value is "inlined" directly into the code wherever it's used, meaning there's no runtime overhead to access the variable. This provides a performance benefit.

Here are the key characteristics of a `const` property:

- It must be a `val` (immutable).
- It must be a top-level property, or a member of an `object` or a `companion object`.
- It must be initialized with a primitive type (`String`, `Int`, `Boolean`, etc.) or a `String`.
- The value must be known at compile time.

**Example:**

```kotlin
const val APP_NAME = "My Awesome App"

fun printAppName() {
    // The compiler replaces 'APP_NAME' with the literal "My Awesome App"
    println(APP_NAME)
}
```

---

## What is a reified keyword in Kotlin?

The `reified` keyword in Kotlin is used with inline functions to access type information at runtime for a generic type parameter. Normally, generic type information is erased at compile time (a concept known as type erasure in the JVM). This means you cannot check the type of a generic parameter at runtime with operators like `is` or `as`.

By marking an inline function's type parameter as `reified`, the compiler replaces the generic type with its actual type during inlining, making it available for checks and operations at runtime.

**Example:**

```kotlin
// This will not compile due to type erasure
// fun <T> findByType(list: List<Any>): T? {
//    return list.find { it is T } // ERROR: Cannot check for T
// }

// With 'reified' in an inline function, it works
inline fun <reified T> findByType(list: List<Any>): T? {
    // The type 'T' is available at runtime
    return list.find { it is T } as T?
}

// Usage:
val myNumbers = listOf(1, "hello", 2, true)
val firstString: String? = findByType<String>(myNumbers)
```

---

## Suspending vs Blocking in Kotlin Coroutines

The main difference between suspending and blocking in Kotlin Coroutines is how they manage the underlying thread's execution.

- **Suspending**: A suspending function (marked with the `suspend` keyword) can pause its execution without blocking the thread it's running on. This is the core of coroutine efficiency. When a suspending function needs to wait for a result (e.g., a network call), it "suspends" the coroutine, freeing the thread to perform other work. When the result is ready, the coroutine can resume on the same or a different thread. This leads to efficient resource utilization and non-blocking I/O.

- **Blocking**: A blocking operation stops the thread's execution completely until the operation is finished. While the thread is blocked, it cannot do any other work. Using blocking calls on the main thread, for instance, will freeze the UI and can lead to an "Application Not Responding" (ANR) error. Blocking is simple but can be inefficient and should be avoided for long-running operations.

In summary, suspending is a cooperative mechanism that allows a thread to be shared among many coroutines, while blocking is a more traditional, exclusive approach where one thread is dedicated to a single task.

---

## Launch vs Async in Kotlin Coroutines

`launch` and `async` are coroutine builders used to start a new coroutine. The key difference lies in how they handle their return value and the purpose they serve.

- **launch**: This is a "fire-and-forget" coroutine builder. It returns a `Job` object, which represents the coroutine's lifecycle and allows you to cancel or wait for its completion. `launch` is used for tasks that don't need to return a result to the caller, such as updating a database, logging, or performing a UI-related action. It's a non-blocking way to start a task.

- **async**: This coroutine builder is used for tasks that need to return a result. It returns a `Deferred<T>` object, which is a lightweight non-blocking future. You can retrieve the result of the computation by calling `.await()` on the `Deferred` object. This function suspends the coroutine until the result is available. `async` is ideal for performing multiple asynchronous tasks in parallel and then waiting for all their results.

**Analogy**: Think of `launch` as sending an email—you send it and don't wait for a reply. `async` is like asking a question—you ask it and then wait for an answer.

---

## internal visibility modifier in Kotlin

The `internal` visibility modifier in Kotlin restricts the visibility of a declaration to the current module. A module is a set of Kotlin files that are compiled together, such as:

- An Android Studio module.
- A Maven or Gradle project.
- A set of files compiled by one `kotlinc` invocation.

If you declare a class, function, or property as `internal`, it can be accessed from any file within the same module, but it's not visible to code outside of that module. This is useful for encapsulating implementation details within a project without exposing them to other projects or libraries.

**Example:**

```kotlin
// Module 'app-module'
internal class InternalService {
    internal fun doInternalWork() {
        // ...
    }
}
```

In another module, say `feature-module`, you would not be able to access `InternalService` or `doInternalWork()`.

---

## open keyword in Kotlin

The `open` keyword in Kotlin is used to make a class or a class member (property or function) open for inheritance. By default, all classes and members in Kotlin are `final`, which means they cannot be subclassed or overridden. This is a design choice to promote composition over inheritance and prevent unexpected behavior caused by subclassing.

To allow a class to be extended or a member to be overridden, you must explicitly mark it with the `open` keyword.

**Example:**

```kotlin
// This class can be inherited
open class Animal {
    // This function can be overridden
    open fun makeSound() {
        println("The animal makes a sound")
    }
}

// Dog can inherit from Animal
class Dog : Animal() {
    // This function overrides the base class's function
    override fun makeSound() {
        println("Woof!")
    }
}
```

---

## lateinit vs lazy in Kotlin

`lateinit` and `lazy` are both ways to initialize a non-null property in Kotlin at a later point, but they serve different purposes and have distinct characteristics.

| Feature          | `lateinit`                                      | `lazy`                                           |
|------------------|-------------------------------------------------|--------------------------------------------------|
| **Purpose**      | Used when you know the property will be initialized before its first use, but its value cannot be set in the constructor. Common for dependency injection. | Used for a property whose value is expensive to create and you want to initialize it only when it's first accessed. |
| **Type**         | Can only be used with `var` (mutable) properties. | Can only be used with `val` (immutable) properties. |
| **Nullability**  | Must be a non-nullable type. No null check is needed, but an exception will be thrown if accessed before initialization. | The property is non-nullable and guaranteed to be initialized on first access. |
| **Thread Safety**| Not thread-safe by default.                     | Thread-safe by default. The lazy delegate provides different modes (`SYNCHRONIZED`, `PUBLICATION`, `NONE`) to control this. |
| **Usage Example**| `lateinit var myService: MyService`             | `val myExpensiveObject: SomeObject by lazy { SomeObject() }` |

**Summary**: Use `lateinit` for mutable properties that will be initialized externally, and `lazy` for immutable, expensive-to-create properties that you want to initialize on demand.

---

## What is Multidex in Android?

Multidex is a mechanism in Android that allows an app to use more than 65,536 method references. This limit is due to the Dalvik Executable (DEX) file format, which has a 16-bit field for indexing methods.

When an app grows in size and complexity—due to its own code, libraries, and frameworks—it can exceed this method count limit. When this happens, the compiler will fail with an error. Multidex solves this by generating multiple DEX files for the app. The primary DEX file contains the initial code and a reference to load additional DEX files, allowing the app to bypass the 65k limit.

You enable it by adding `multiDexEnabled true` to your app-level `build.gradle` file.

---

## How does the Android Push Notification system work?

The Android Push Notification system works through a chain of communication between your app server, a cloud messaging service, and the user's device. Here's the general flow:

1. **Registration**: When a user's device registers with your app, the app's backend server sends a request to a cloud messaging service, such as Firebase Cloud Messaging (FCM), to obtain a unique registration token for that device.

2. **Message Creation**: Your app server or a third-party server decides to send a push notification. It creates a message payload containing the notification content (title, body, etc.) and the device's unique registration token.

3. **Sending**: The app server sends the message payload to the cloud messaging service.

4. **Delivery**: The cloud messaging service (FCM) receives the message and pushes it to the target Android device via a persistent connection. This service is part of the Android OS and is highly optimized to handle notifications efficiently, even when the device is in a low-power state.

5. **Reception**: The Android OS receives the message. If the app is in the background, the OS displays the notification in the notification bar. If the app is in the foreground, the message is delivered directly to your app's code for you to handle programmatically.

---

## How does the Kotlin Multiplatform work?

Kotlin Multiplatform (KMP) is a technology by JetBrains that allows developers to share code across multiple platforms while keeping the user interface (UI) native. It works by having a core "common" module where you write business logic, networking, data handling, and other non-UI code in Kotlin.

KMP uses a set of compilers to translate this common Kotlin code into platform-specific binaries:

- **Kotlin/JVM**: Compiles Kotlin code into JVM bytecode for Android, desktop, and backend applications.
- **Kotlin/Native**: Compiles Kotlin code into native binaries for platforms like iOS, macOS, watchOS, and Linux. This allows direct access to platform APIs and interoperability with languages like Swift and Objective-C.
- **Kotlin/JS**: Compiles Kotlin code to JavaScript for web applications.

For platform-specific features that can't be implemented in the common module (e.g., accessing a device's camera or a platform-specific API), KMP uses the `expect`/`actual` mechanism. You declare an `expect` function or class in the common module, and then provide a platform-specific `actual` implementation in each platform module. This allows you to write the same high-level logic and call the appropriate native implementation transparently.

---

## What is a ViewModel and how is it useful?

A `ViewModel` is a class from the Android Jetpack Architecture Components library. It is designed to store and manage UI-related data in a lifecycle-aware way.

Its primary purpose is to survive configuration changes, such as screen rotations. When an Activity or Fragment is destroyed and recreated due to a configuration change, the `ViewModel` instance is retained. This prevents you from losing the data you've fetched or processed, and avoids unnecessary network calls or database queries.

**Key advantages**:

- **Lifecycle Awareness**: It can observe the lifecycle of a Fragment or Activity and hold data until the associated Activity or Fragment is completely finished (e.g., the user navigates away).
- **Separation of Concerns**: It separates the UI logic (Activity/Fragment) from the business logic and data handling, making the code cleaner, more testable, and easier to maintain.
- **Data Persistence**: It ensures that data is not lost on configuration changes, providing a better user experience.

---

## Is it possible to force Garbage Collection in Android?

No, you cannot truly force garbage collection (GC) in Android. You can only suggest it to the system by calling `System.gc()` or `Runtime.getRuntime().gc()`.

However, these calls are just a hint, and the Android runtime is highly optimized to decide when the best time to run the GC is. Calling it yourself is generally discouraged as it can introduce performance issues, like temporary UI stuttering, by unexpectedly interrupting the system's operations. The system's garbage collector is designed to run automatically and efficiently when needed, such as when heap memory is getting low.

A better practice is to focus on avoiding memory leaks by properly managing object lifecycles, and allowing the system to handle memory cleanup on its own.

---

## What is a JvmStatic Annotation in Kotlin?

The `@JvmStatic` annotation in Kotlin is used to expose a function or property defined inside a companion object or a named object as a static member to Java code.

In Kotlin, companion objects and named objects are compiled as singleton classes. Their members are instance methods of these singleton classes, not true static methods. `@JvmStatic` instructs the Kotlin compiler to generate a true static method for a function or a static field for a property in the bytecode, making it directly callable from Java without needing the `INSTANCE` singleton reference.

**Example:**

```kotlin
// Kotlin code
class MyClass {
    companion object {
        @JvmStatic
        fun myStaticMethod() {
            println("Hello from a static method")
        }
    }
}

// Java code
// Can be called directly without the `INSTANCE`
MyClass.myStaticMethod();
```

---

## init block in Kotlin

The `init` block in Kotlin is a special block of code that is executed as part of a class's primary constructor. It's used to put initialization code that can't be placed directly in the primary constructor's parameter list.

When a new instance of a class is created, the `init` block runs immediately after the primary constructor's parameters are processed. If a class has multiple `init` blocks, they are executed sequentially in the order they appear in the class body.

**Example:**

```kotlin
class User(name: String) {
    val username: String

    init {
        // This code runs when the class is initialized
        username = name.toUpperCase()
        println("User '$username' has been created.")
    }
}

// Creating an instance will print the message
val user = User("john doe")
// Output: User 'JOHN DOE' has been created.
```

---

## JvmField Annotation in Kotlin

The `@JvmField` annotation in Kotlin is used to expose a property as a public field in Java, rather than as a property with generated getters and setters.

By default, Kotlin properties are compiled with getters (for `val` properties) and both getters and setters (for `var` properties). This is part of Kotlin's property-based design. When you need to interact with a Java library that expects a public field, or for performance-critical scenarios where direct field access is more efficient, `@JvmField` can be used.

**Example:**

```kotlin
// Kotlin code
class MyData {
    // This will be a public field in Java
    @JvmField
    val myName: String = "John"
}

// Java code
// Direct access to the field, no getter is generated
MyData myData = new MyData();
String name = myData.myName;
```

This annotation can only be used on non-private properties, and it cannot be used with properties that have custom getters or setters.

---

## singleTask launchMode in Android

`singleTask` is an Android Activity launch mode. It dictates how a new instance of an activity is created and managed within the Android task stack.

When an activity with `singleTask` launch mode is started:

- The system searches for an existing instance of this activity in the current task stack.
- If an instance exists, the system does not create a new one. Instead, it brings the existing instance to the top of the stack and calls its `onNewIntent()` method. All other activities on top of this instance in the stack are destroyed.
- If an instance does not exist, a new instance is created and placed at the top of the stack.

`singleTask` is useful for activities that should have only one instance running at a time, such as a main dashboard or home screen. It prevents the creation of duplicate instances and ensures a consistent user experience.

---

## Difference between == and === in Kotlin

In Kotlin, `==` and `===` perform different types of equality checks.

- **`==` (Structural Equality)**: This operator checks if the content of two objects is the same. It is translated to a call to the `.equals()` method. For primitive types, it performs a simple value comparison. For data classes, `==` automatically checks for equality of all properties.

- **`===` (Referential Equality)**: This operator checks if two references point to the exact same object in memory. It's a strict identity comparison. For primitive types, `===` is the same as `==`.

**Example:**

```kotlin
val a = "hello"
val b = "hello"
val c = a

println(a == b) // true (content is the same)
println(a === b) // true (in this case, string literal optimization makes them the same object)

val list1 = listOf(1, 2, 3)
val list2 = listOf(1, 2, 3)

println(list1 == list2) // true (structural equality, content is the same)
println(list1 === list2) // false (referential equality, they are different objects in memory)
```

---

## JvmOverloads Annotation in Kotlin

The `@JvmOverloads` annotation in Kotlin is used to improve interoperability with Java. When you have a Kotlin function with default parameter values, the Kotlin compiler generates only a single function with all parameters. This can be problematic for Java callers, who can't use the default values.

By adding `@JvmOverloads`, you instruct the Kotlin compiler to generate multiple overloaded methods for that function in the bytecode. Each overloaded method will have a different number of parameters, corresponding to the default values you've provided. This allows Java code to call the function with any number of parameters, just like a standard overloaded Java method.

**Example:**

```kotlin
// Kotlin code
class Greeter {
    @JvmOverloads
    fun sayHello(message: String = "Hello", name: String = "World") {
        println("$message, $name!")
    }
}

// Java code
Greeter greeter = new Greeter();
greeter.sayHello(); // Calls sayHello(String, String) with default values
greeter.sayHello("Hi"); // Calls sayHello(String, String) with "Hi" and default name
greeter.sayHello("Hi", "John"); // Calls sayHello(String, String)
```

---

## Why is it recommended to use only the default constructor to create a Fragment?

It is strongly recommended to use only the default (no-argument) constructor to create a Fragment because of how the Android system handles fragment lifecycle and state restoration.

When Android needs to recreate an Activity (e.g., after a configuration change or process death), it also needs to recreate its Fragments. The system does this by using reflection to find and call the fragment's default constructor. If you use a parameterized constructor, the system won't know how to pass the necessary arguments, leading to a `Fragment.InstantiationException` and a crash.

To pass data to a Fragment, the correct and safe approach is to use a `Bundle` and the `setArguments()` method. This Bundle is automatically saved and restored by the system, ensuring that the data is available when the fragment is recreated.

**Best Practice:**

```kotlin
class MyFragment : Fragment() {
    companion object {
        fun newInstance(data: String): MyFragment {
            val fragment = MyFragment()
            val args = Bundle()
            args.putString("key_data", data)
            fragment.arguments = args
            return fragment
        }
    }
}
```

---

## Why do we need to call setContentView() in onCreate() of Activity class?

You need to call `setContentView()` in the `onCreate()` method of an Activity because it's the method that sets the user interface layout for the activity.

The `onCreate()` method is the first lifecycle callback, called when the activity is being created. It's the ideal place to perform all your essential setup, and setting the content view is a critical part of that. The `setContentView()` method takes a layout resource ID and inflates the XML layout file, attaching it to the activity's window. Without this call, your activity would have no UI to display.

---

## When only onDestroy is called for an activity without onPause() and onStop()?

It is rare for an Activity's `onDestroy()` to be called without `onPause()` and `onStop()` first, as the normal lifecycle flow is `onPause()` → `onStop()` → `onDestroy()`. However, this can happen when the Android system decides to kill the app's process entirely for memory-reclamation purposes.

This scenario, often referred to as "process death," can occur when the app has been in the background for a long time and the system needs to free up resources for other apps. In this case, the system doesn't bother with the orderly shutdown of each component's lifecycle methods (`onPause()`, `onStop()`) and simply terminates the process.

This is a key reason why you should always save important state and data in `onPause()` or `onStop()` and not rely on `onDestroy()` to be called.

---

## Master Kotlin Coroutines

### Suspending vs. Blocking in Kotlin Coroutines

Suspending and blocking are two distinct ways to handle concurrent operations. The key difference lies in how they manage the underlying thread.

- **Suspending**: A suspending function (marked with the `suspend` keyword) can pause its execution without blocking the thread it's running on. When a suspending function needs to wait for a result (e.g., a network call or a database query), it releases the thread to perform other work. When the result is ready, the coroutine can resume on the same or a different thread. This is a cooperative mechanism that allows a single thread to be shared by many coroutines, making it highly efficient for I/O-bound tasks.

- **Blocking**: A blocking operation completely stops the thread's execution until the task is complete. While the thread is blocked, it cannot perform any other work. If a blocking call is made on the main thread, the UI will freeze, potentially leading to an "Application Not Responding" (ANR) error. Blocking is simple but can be inefficient and should be avoided for long-running operations.

In short, a suspending function is a non-blocking alternative to a blocking function, allowing for a more efficient and responsive application.

---

### Launch vs. Async in Kotlin Coroutines

`launch` and `async` are both coroutine builders used to start a new coroutine, but they serve different purposes based on their return type.

- **launch**: This builder is used for "fire-and-forget" tasks that don't need to return a result to the caller. It returns a `Job` object, which represents the coroutine's lifecycle. A Job can be used to cancel or wait for the coroutine to complete, but it doesn't hold a value. Use `launch` for tasks like updating UI, logging, or saving data to a local database.

- **async**: This builder is used when the coroutine is expected to return a result. It returns a `Deferred<T>` object, which is a non-blocking future. You can get the result by calling the `await()` function on the `Deferred` object. This call suspends the current coroutine until the result is available. Use `async` when you need to perform multiple asynchronous tasks in parallel and then process their results, such as making two concurrent network calls.

**Analogy**: Think of `launch` as sending an email—you send it and don't necessarily wait for a reply. `async` is like asking a question—you ask it and then wait for an answer.

---

### Dispatchers in Kotlin Coroutines

Dispatchers are a key part of Kotlin Coroutines. A Dispatcher determines which thread or thread pool the coroutine will use for its execution. They are a crucial component for managing concurrency and ensuring your code runs on the correct thread.

Kotlin provides three main dispatchers:

- **`Dispatchers.Main`**: This dispatcher is tied to the main thread of an Android application. It should be used for all UI-related work, such as updating views or handling user input. Performing long-running operations on this dispatcher will freeze the UI.

- **`Dispatchers.IO`**: This dispatcher is optimized for I/O-intensive tasks, like network calls, reading or writing to a file, or database operations. It uses a thread pool that is suitable for a large number of blocking I/O operations.

- **`Dispatchers.Default`**: This dispatcher is optimized for CPU-intensive tasks, such as sorting a large list, complex calculations, or image processing. It uses a shared thread pool with a number of threads equal to the number of CPU cores.

You can specify a dispatcher using the `withContext` or `launch` builders.

---

### coroutineScope vs. supervisorScope

`coroutineScope` and `supervisorScope` are builders used to create a new coroutine scope with structured concurrency. The primary difference is how they handle coroutine failures.

- **coroutineScope**: This builder creates a new scope and waits for all of its child coroutines to complete before it completes itself. If any of the child coroutines fails with an exception, the exception is immediately propagated to the parent coroutine, which then cancels all its other children. This "fail-fast" behavior ensures that a failure in one part of the scope brings down the entire scope.

- **supervisorScope**: This builder is similar to `coroutineScope`, but it has a key distinction: a failure in one of its children does not cause the supervisor scope to fail. Instead, the exception is propagated only to the failing child's parent, and other children in the scope continue to run. This is useful when you have independent tasks within a scope, and you want a failure in one to not affect the others.

**Analogy**: Think of `coroutineScope` as a team project where if one person fails, the whole project is abandoned. `supervisorScope` is like a team where if one person fails, a supervisor handles their error, but the rest of the team continues working.

---

### Suspend Function in Kotlin Coroutines

A suspend function is a function that can be paused and resumed at a later time. It is a fundamental building block of Kotlin Coroutines. The `suspend` keyword is a signal to the compiler that this function can execute long-running operations in a non-blocking way.

`suspend` functions can only be called from within a coroutine or another suspend function. This ensures that the code's asynchronous nature is explicit and properly managed. When a suspend function is called, it might "suspend" the coroutine, freeing the thread, and will "resume" when its work is done. This makes it possible to write asynchronous code that looks sequential and easy to read.

**Example:**

```kotlin
// This function suspends the coroutine until the network call is complete
suspend fun fetchUserData(): User {
    // This is a suspend function from a library
    return apiService.getUser()
}
```

---

### Kotlin withContext vs. async-await

Both `withContext` and `async-await` are used to switch between dispatchers and execute a block of code, but they serve different purposes.

- **withContext**: This is a direct, sequential way to switch the coroutine's context. The block of code inside `withContext` is executed on the specified dispatcher, and the calling coroutine is suspended until the block completes. The result of the block is returned immediately. `withContext` is ideal for moving a single, sequential operation (like a network call) to a different thread.

- **async-await**: This is used for parallel execution. `async` starts a new coroutine on the specified dispatcher and returns a `Deferred` object immediately. The calling coroutine continues to run. When you need the result, you call `await()` on the `Deferred` object, which suspends the coroutine until the result is ready. `async-await` is perfect for concurrent operations.

**Example:**

```kotlin
// withContext (sequential)
suspend fun fetchUserAndPost() {
    val user = withContext(Dispatchers.IO) { api.getUser() }
    val post = withContext(Dispatchers.IO) { api.getPost(user.id) }
    // ...
}

// async-await (parallel)
suspend fun fetchUserAndPostConcurrently() {
    val userDeferred = async(Dispatchers.IO) { api.getUser() }
    val postDeferred = async(Dispatchers.IO) { api.getPost() }

    val user = userDeferred.await()
    val post = postDeferred.await()
    // ...
}
```

---

### CoroutineContext in Kotlin

A `CoroutineContext` is a set of elements that define the behavior of a coroutine. It acts as a collection of key-value pairs where each key is a `CoroutineContext.Key` and the value is the corresponding `CoroutineContext.Element`.

The main elements of a `CoroutineContext` are:

- **Job**: Manages the coroutine's lifecycle and allows for cancellation.
- **Dispatcher**: Determines the thread or thread pool on which the coroutine will run.
- **CoroutineName**: A helpful debugging tool for naming a coroutine.
- **CoroutineExceptionHandler**: Catches uncaught exceptions in a coroutine.

A `CoroutineContext` can be combined using the `+` operator. For example, `Dispatchers.IO + Job()` creates a new context. This allows for granular control over a coroutine's behavior, making it highly flexible.

---

### Callback to Coroutines in Kotlin

You can convert a callback-based API into a coroutine-friendly, suspending function using a technique called `suspendCoroutine`. This function, provided by the `kotlinx.coroutines` library, suspends the current coroutine and provides a `Continuation` object. You can then use this `Continuation` to resume the coroutine with a result or an exception once the callback is triggered.

**Example:**

```kotlin
// Old callback-based API
fun fetchData(callback: (Result) -> Unit) { /* ... */ }

// Wrapping with suspendCoroutine
suspend fun fetchDataCoroutines(): Result = suspendCoroutine { continuation ->
    fetchData { result ->
        continuation.resume(result) // Resumes the coroutine with the result
    }
}
```

While `suspendCoroutine` is powerful, libraries often provide dedicated coroutine-friendly APIs (like Retrofit's suspend functions).

---

### Retrofit with Kotlin Coroutines

Retrofit, a popular Android networking library, has excellent support for Kotlin Coroutines. Instead of using `Call` objects and callbacks, you can simply add the `suspend` keyword to your interface functions.

When Retrofit encounters a suspend function, it automatically handles the asynchronous network call in a coroutine-friendly way. It performs the I/O operation on a background thread (usually in `Dispatchers.IO`) and returns the result, suspending the coroutine until the call is complete. This makes your network code much cleaner, more readable, and sequential.

**Example:**

```kotlin
interface ApiService {
    // Suspend function that makes a network call
    @GET("users/{id}")
    suspend fun getUser(@Path("id") userId: String): User
}

// Calling the suspend function from a ViewModel
viewModelScope.launch {
    try {
        val user = apiService.getUser("123")
        // Update UI
    } catch (e: Exception) {
        // Handle error
    }
}
```

---

### Parallel Multiple Network Calls Using Kotlin Coroutines

Kotlin Coroutines make parallel network calls easy and efficient using the `async-await` pattern. Instead of making one network call and waiting for it to finish before starting the next, you can launch multiple `async` coroutines in parallel.

The process is as follows:

1. Launch a coroutine using a coroutine scope (e.g., `viewModelScope`).
2. Use `async` for each network call that you want to run in parallel. Each `async` block will return a `Deferred` object.
3. Call `await()` on each `Deferred` object to get the results. The `await()` function will suspend the current coroutine until the result is available. Because the network calls were started in parallel, this step is non-blocking and efficient.

**Example:**

```kotlin
viewModelScope.launch {
    try {
        val userDeferred = async(Dispatchers.IO) { apiService.getUser("123") }
        val postsDeferred = async(Dispatchers.IO) { apiService.getUserPosts("123") }

        val user = userDeferred.await()
        val posts = postsDeferred.await()
        // Process results
    } catch (e: Exception) {
        // Handle error
    }
}
```

---

### Room Database with Kotlin Coroutines

Room, the Android Jetpack persistence library, has built-in support for Kotlin Coroutines. By marking your DAO (Data Access Object) functions with the `suspend` keyword, Room automatically handles the database operation on a background thread.

This simplifies your database access code and ensures that you don't perform long-running database queries on the main thread, preventing ANRs. Room's coroutine support makes your data layer code clean, sequential, and safe.

**Example:**

```kotlin
@Dao
interface UserDao {
    @Query("SELECT * FROM user WHERE id = :userId")
    suspend fun getUser(userId: Int): User

    @Insert
    suspend fun insertUser(user: User)
}

// Call from ViewModel
viewModelScope.launch(Dispatchers.IO) {
    val user = userDao.getUser(1)
    // Update UI or process data
}
```

---

### Unit Testing ViewModel with Kotlin Coroutines and LiveData

Unit testing a ViewModel that uses LiveData and coroutines requires a few specific tools to manage threading and lifecycle.

- **TestCoroutineDispatcher**: This is a special dispatcher from `kotlinx.coroutines.test` that allows you to control the execution of your coroutines in a predictable, synchronous manner. You can use methods like `runBlockingTest` or `advanceUntilIdle` to ensure all coroutines have completed before making assertions.

- **InstantTaskExecutorRule**: This JUnit rule from AndroidX Test is used to make LiveData operations happen synchronously. By default, LiveData works on a background thread, which can make testing difficult. This rule forces all LiveData tasks to execute on the same thread, making tests deterministic.

- **Dependency Injection**: Use mock objects for your repository or data source dependencies. This isolates the ViewModel and allows you to test its specific logic without relying on real network or database calls.

By combining these tools, you can write reliable, repeatable unit tests for your ViewModel that correctly handle the complexities of LiveData and coroutines.

---

## What is Coroutines?

Coroutines are a concurrency design pattern in Kotlin that allows you to write asynchronous, non-blocking code in a sequential and easy-to-read manner. They are a lightweight alternative to traditional threads.

### Key Concepts

#### Lightweight

Coroutines are managed by the Kotlin runtime, not the operating system, making them much less resource-intensive than threads. You can run thousands of coroutines on a single thread, whereas creating a new thread for every task would quickly consume system memory and lead to performance issues.

#### Structured Concurrency

Coroutines promote structured concurrency, a programming paradigm that organizes concurrent tasks in a hierarchy. When you launch a coroutine, it runs within a `CoroutineScope`. This scope acts as a parent for the coroutine, and when the scope is canceled, all child coroutines are also canceled. This prevents resource leaks and simplifies error handling.

#### Suspending Functions

The core of coroutines are suspending functions, marked with the `suspend` keyword. A suspending function can be paused and resumed at a later time. When a suspend function needs to wait for a result (e.g., from a network request), it suspends the coroutine, freeing up the underlying thread to do other work. When the result is ready, the coroutine can resume its execution. This non-blocking behavior is a key advantage.

### Coroutines vs. Threads

| Feature           | Coroutines                         | Threads                          |
|-------------------|------------------------------------|----------------------------------|
| **Execution**     | Cooperative                        | Preemptive                       |
| **Resource Usage**| Lightweight                        | Heavyweight                      |
| **Cancellation**  | Structured and easy                | Difficult and error-prone        |
| **Scope**         | Coroutine Scope                    | OS-level process                 |

While threads are managed by the operating system and are a unit of CPU execution, coroutines are managed by the application code and are a unit of work. Think of a thread as a physical assembly line in a factory, whereas a coroutine is a single task or item on that line. A few assembly lines can handle a vast number of tasks efficiently.

---

## withContext

`withContext` is a suspending function in Kotlin Coroutines that allows you to change the `CoroutineContext` of the current coroutine. It's primarily used to switch to a different thread or thread pool (a different `Dispatcher`) for a specific block of code and then return to the original context when the block is finished.

### How It Works

When you call `withContext`, it suspends the current coroutine. The code block you pass to `withContext` is then executed on the specified dispatcher. Once that block finishes and returns a result, the coroutine is resumed on its original context. This makes it an ideal tool for moving a long-running operation from a UI thread to a background thread without blocking the UI.

The `withContext` function returns the result of the code block it executes.

### Example

Imagine you need to perform a network request and then update the UI. The network call is an I/O operation and should run on `Dispatchers.IO`, while the UI update must be on `Dispatchers.Main`. `withContext` handles this switch seamlessly.

```kotlin
suspend fun fetchUserDataAndDisplay() {
    // Coroutine starts on Dispatchers.Main (or another context)
    val user = withContext(Dispatchers.IO) {
        // Now running on the I/O thread pool
        // This is a suspend function, and the coroutine will suspend here
        apiService.getUser("123")
    }
    // Automatically resumes on the original context (e.g., Dispatchers.Main)
    // The UI is safe to update now
    updateUI(user)
}
```

### withContext vs. async

While both can switch dispatchers, their primary purposes differ.

| **withContext** | **async** |
|------------------|-----------|
| Best for a single, sequential operation. It's a "suspending block" that ensures the operation completes before the rest of the code continues. | Best for running tasks in parallel. `async` launches a new coroutine that runs concurrently with the original one. You then use `await()` to get the result when needed. |

---

## Exception Handling in Coroutines

Exception handling in Kotlin Coroutines follows a structured approach based on the coroutine hierarchy and structured concurrency. Unlike traditional thread-based systems where exceptions can be swallowed or lead to silent crashes, coroutines provide predictable and explicit mechanisms to deal with errors.

### Exception Propagation

When a coroutine throws an unhandled exception, it's propagated up the coroutine hierarchy. The coroutine's `Job` acts as its parent. When a child coroutine fails with an exception, the parent `Job` is immediately canceled. This cancellation then cascades to all other sibling coroutines, ensuring that all related tasks are stopped to prevent inconsistent state.

This "fail-fast" behavior is the default and is a core part of structured concurrency. It prevents silent failures and helps in debugging.

### Handling Exceptions with try-catch

The most common and straightforward way to handle exceptions in a coroutine is by using a standard `try-catch` block. This is useful for handling exceptions from a specific section of code, such as a network or database call.

```kotlin
import kotlinx.coroutines.*

fun main() = runBlocking {
    val job = launch {
        try {
            // Code that might throw an exception
            println("Making a network call...")
            delay(500) // Simulate work
            throw IllegalStateException("Network call failed!")
        } catch (e: Exception) {
            // Handle the exception
            println("Caught exception: ${e.message}")
        }
    }
    job.join()
}
```

### The CoroutineExceptionHandler

For handling exceptions that are not caught by a `try-catch` block, you can use a `CoroutineExceptionHandler`. This is an optional element you can add to a coroutine's `CoroutineContext`. It acts as a global handler for a specific coroutine or a coroutine scope.

When a child coroutine fails, the exception is passed to the `CoroutineExceptionHandler` if one is defined.

```kotlin
import kotlinx.coroutines.*

fun main() = runBlocking {
    val handler = CoroutineExceptionHandler { _, exception ->
        println("Caught an unhandled exception: ${exception.message}")
    }

    val scope = CoroutineScope(Dispatchers.Main + Job() + handler)

    scope.launch {
        // This will be caught by the handler
        throw IllegalArgumentException("Something went wrong!")
    }

    delay(1000)
    scope.cancel()
}
```

### Special Cases

#### async and await()
With `async`, exceptions are not immediately propagated. They are captured and stored inside the `Deferred` object. The exception is only re-thrown when you call `await()`. This allows you to handle exceptions at the point where you retrieve the result, which is useful for parallel operations.

```kotlin
val deferred = async {
    throw IOException("Network error")
}

try {
    deferred.await() // Exception is re-thrown here
} catch (e: Exception) {
    println("Caught exception on await: ${e.message}")
}
```

#### SupervisorJob
When using a `supervisorScope` or a `SupervisorJob`, an exception in a child coroutine does not cancel its siblings or its parent. This is useful for building isolated, independent tasks within a single scope where a failure in one shouldn't affect the others. The exception is still propagated up and can be handled by a `CoroutineExceptionHandler` on the `SupervisorJob`.

---

### Practical Comparison: supervisorScope vs coroutineScope

#### With `supervisorScope`
```kotlin
launch {
    supervisorScope {
        val usersDeferred = async { getUsers() }
        val moreUsersDeferred = async { getMoreUsers() }

        val users = try {
            usersDeferred.await()
        } catch (e: Exception) {
            emptyList<User>()
        }

        val moreUsers = try {
            moreUsersDeferred.await()
        } catch (e: Exception) {
            emptyList<User>()
        }
    }
}
```

**Behavior**  
- A failure in one child coroutine (e.g., `usersDeferred`) does not affect siblings or the parent scope.  
- Exceptions are handled locally via `try-catch`, allowing other coroutines to continue.  
✅ **Use Case**: Ideal for independent, parallel tasks (e.g., loading multiple unrelated data sources).

---

#### With `coroutineScope`
```kotlin
launch {
    coroutineScope {
        val usersDeferred = async { getUsers() }
        val moreUsersDeferred = async { getMoreUsers() }

        val users = try {
            usersDeferred.await()
        } catch (e: Exception) {
            emptyList<User>()
        }

        val moreUsers = try {
            moreUsersDeferred.await()
        } catch (e: Exception) {
            emptyList<User>()
        }
    }
}

**Behavior**  
- A failure in one child coroutine (e.g., `usersDeferred`) cancels all siblings and the parent scope.  
- Even with `try-catch`, canceled coroutines (e.g., `moreUsersDeferred`) will throw `CancellationException`.  
✅ **Use Case**: Best for interdependent operations (e.g., fetching primary data and metadata) where failure invalidates others.


## 🎯 Kotlin Language Fundamentals

### val vs var

The difference between `val` and `var` in Kotlin is about mutability.

- **`val` (from "value"):** Used to declare an **immutable** variable, meaning its value can be assigned only once. It's similar to `final` in Java. You should prefer `val` whenever possible, as it leads to safer and more predictable code.
- **`var` (from "variable"):** Used to declare a **mutable** variable, meaning its value can be reassigned multiple times.

**Example:**

```kotlin
val name = "Alice" // Cannot be reassigned
// name = "Bob" // This would be a compilation error

var age = 30 // Can be reassigned
age = 31 // This is fine
```

---

### Advantage of Using const

The **`const`** keyword in Kotlin is used to declare a compile-time constant. It has two main advantages:

1. **Compile-time optimization:** The value of a `const` property is inlined directly at the call site during compilation. This means there's no runtime overhead to access the value, as it's hardcoded into the bytecode.
2. **Java Interoperability:** A `const` property is compiled as a `public static final` field in Java, making it easily accessible from Java code.

**Example:**

```kotlin
const val API_KEY = "my_secret_key"

fun connectToApi() {
    // The value "my_secret_key" is inlined here at compile time
    println("Connecting with key: $API_KEY") 
}
```

A `const` property can only be a `String` or a primitive type and must be declared at the top level or within a `companion object`.

---

### String vs StringBuffer vs StringBuilder

| Feature          | **String** | **StringBuffer** | **StringBuilder** |
|------------------|----------------------------------------------|----------------------------------------------|--------------------------------------------|
| **Mutability** | **Immutable**. Once created, it cannot be changed. | **Mutable**. Can be changed in place. | **Mutable**. Can be changed in place. |
| **Thread-Safety**| N/A (immutable).                            | **Thread-safe**. Methods are synchronized.  | **Not thread-safe**. |
| **Performance** | Slower for many modifications due to new object creation. | Slower than `StringBuilder` due to synchronization overhead. | Fastest option for mutable strings in single-threaded environment. |
| **Use Case** | Default choice for static text or infrequent modifications. | Multi-threaded environments.                | Single-threaded environments where you need to build a string dynamically. |

**Example:**

```kotlin
val sentence = StringBuilder()
sentence.append("Hello")
sentence.append(" ")
sentence.append("World")
println(sentence.toString()) // Prints: Hello World
```

---

### == vs === (Equality Operators)

The `==` and `===` operators in Kotlin are used for comparison, but they check for different things:

- **`==` (Structural Equality):** Checks if two objects have the same content or value. For objects, it calls the `equals()` method.
- **`===` (Referential Equality):** Checks if two objects are the exact same instance in memory.

**Example:**

```kotlin
val a = "Hello"
val b = "Hello"
val c = String("Hello".toCharArray())

println(a == b)  // true (same value)
println(a == c)  // true (same value)
println(a === b) // true (JVM optimization)
println(a === c) // false (c is a new instance)
```

---

### Elvis Operator (?:)

The **Elvis operator (`?:`)** provides a concise way to return a default value when an expression on its left-hand side is `null`.

**Example:**

```kotlin
val name: String? = null
val displayName = name ?: "Guest" // displayName is "Guest"

val nonNullName: String? = "John"
val anotherName = nonNullName ?: "Guest" // anotherName is "John"
```

---

### Labels

**Labels** are a way to name a loop or a lambda block in Kotlin. They are used to specify which scope a non-local `return` or `break` should apply to.

**Example:**

```kotlin
fun findNumber() {
    val numbers = listOf(1, 2, 3, 4, 5)
    numbers.forEach loop@{
        if (it == 3) {
            return@loop // Returns from the lambda, not the function
        }
        println(it)
    }
    println("This line is printed.")
}
```

---

### Visibility Modifiers

Visibility modifiers control the accessibility of declarations in Kotlin:

1. **`public` (default):** Visible everywhere.
2. **`private`:** Visible only within the file, class, or object where it's declared.
3. **`protected`:** Visible within the class and its subclasses.
4. **`internal`:** Visible within the same module.

**Example:**

```kotlin
private class MySecretClass
internal fun doSomethingInternal() {}
open class Base {
    protected fun protectedMethod() {}
}
```

---

### open keyword

In Kotlin, all classes and functions are **final** by default. The `open` keyword allows a class to be subclassed or a function to be overridden.

**Example:**

```kotlin
open class Vehicle {
    open fun drive() {
        println("Driving a vehicle.")
    }
}

class Car : Vehicle() {
    override fun drive() {
        println("Driving a car.")
    }
}
```

---

### internal visibility modifier

The **`internal`** visibility modifier means that the declared member is visible **within the same module**.

**Example:**

```kotlin
// In module 'app'
internal class Logger {
    fun log(message: String) {
        println(message)
    }
}
```

---

### open vs public

| Feature       | `open`                                        | `public`                                     |
|---------------|-----------------------------------------------|----------------------------------------------|
| **Category** | Inheritance modifier.                         | Visibility modifier.                         |
| **Purpose** | Allows a class to be subclassed or a function to be overridden. | Controls the accessibility of a declaration. |
| **Default** | **No.** Classes and functions are `final` by default. | **Yes.** All declarations are `public` by default. |

---

## 🔧 Kotlin Advanced Features

### inline function

An inline function in Kotlin is a function that the compiler replaces with the actual function body at the call site. This reduces the overhead of lambda expressions.

**Example:**

```kotlin
inline fun calculateInline(a: Int, b: Int, operation: (Int, Int) -> Int): Int {
    return operation(a, b)
}
```

---

### noinline keyword

The `noinline` keyword prevents the compiler from inlining a specific lambda parameter of an inline function.

**Example:**

```kotlin
inline fun doSomething(
    inlineAction: () -> Unit,
    noinline noInlineAction: () -> Unit
) {
    inlineAction() // This lambda is inlined
    // noInlineAction can be passed to other functions
}
```

---

### crossinline keyword

The `crossinline` keyword prevents non-local returns from inside a lambda parameter.

**Example:**

```kotlin
inline fun myInlineFunction(crossinline action: () -> Unit) {
    println("Before action")
    action()
    println("After action")
}
```

---

### reified keyword

The `reified` keyword is used with inline functions to access type information at runtime for a generic type parameter.

**Example:**

```kotlin
inline fun <reified T> getClassName(value: T) {
    println("The class name is ${T::class.simpleName}")
}

getClassName("Hello") // Prints: The class name is String
```

---

### lateinit vs lazy

| Feature        | `lateinit`                                     | `lazy`                                                                 |
|----------------|------------------------------------------------|------------------------------------------------------------------------|
| **Usage** | Used with mutable (`var`) properties.          | Used with immutable (`val`) properties.                                |
| **When to use**| When the property will be initialized later | When the property's initialization is expensive and should only happen on first access |
| **Thread-Safety**| Not thread-safe by default | Thread-safe by default |
| **Null safety**| Must check for initialization before access | Guaranteed to be non-null after first access |

**Example:**

```kotlin
// lateinit:
lateinit var myString: String

// lazy:
val myLazyString: String by lazy {
    println("Initializing...")
    "This is lazy!"
}
```

---

### Checking lateinit Initialization

You can check if a `lateinit` variable has been initialized using its `isInitialized` property.

**Example:**

```kotlin
lateinit var name: String

if (::name.isInitialized) {
    println("Name is initialized.")
}
```

---

### Lazy Initialization

**Lazy initialization** delays the initialization of a property until its first access.

**Example:**

```kotlin
val expensiveComputation by lazy {
    println("Computing...")
    "Result"
}
```

---

### init block

An `init` block is executed as part of a class's primary constructor.

**Example:**

```kotlin
class Person(val name: String) {
    init {
        println("Person $name created")
    }
}
```

---

### Higher-Order Functions

A **higher-order function** is a function that either accepts another function as a parameter or returns a function.

**Example:**

```kotlin
fun calculate(a: Int, b: Int, operation: (Int, Int) -> Int): Int {
    return operation(a, b)
}

val sum = calculate(5, 3) { x, y -> x + y }
```

---

### Function That Returns a Function

**Example:**

```kotlin
fun createGreeter(greeting: String): (String) -> Unit {
    return { name: String ->
        println("$greeting, $name!")
    }
}

val helloGreeter = createGreeter("Hello")
helloGreeter("Alice") // Prints: Hello, Alice!
```

---

### Lambdas

A **lambda expression** is a concise way to define an anonymous function.

**Example:**

```kotlin
val sum = { a: Int, b: Int -> a + b }
val result = sum(10, 5) // result is 15
```

---

### Infix Notation

**Infix notation** is a more readable way to call a function with a single parameter.

**Example:**

```kotlin
infix fun Int.isDivisibleBy(divisor: Int): Boolean {
    return this % divisor == 0
}

println(10 isDivisibleBy 2) // true
```

---

### Delegates

**Delegates** allow one object to delegate some of its functionality to another object.

**Example:**

```kotlin
val myLazyValue: String by lazy {
    "This is computed once."
}

class Manager(private val worker: Worker) : Runnable by worker
```

---

## 🏗️ Kotlin Classes & Objects

### Data Classes

A **data class** automatically generates useful methods like `equals()`, `hashCode()`, `toString()`, and `copy()`.

**Example:**

```kotlin
data class User(val name: String, val age: Int)

val user1 = User("Alice", 30)
val user2 = user1.copy(age = 31)
```

---

### Sealed Classes

A **sealed class** represents a restricted class hierarchy. All subclasses must be defined in the same file.

**Example:**

```kotlin
sealed class Result {
    data class Success(val data: String) : Result()
    data class Error(val message: String) : Result()
    object Loading : Result()
}

fun handleResult(result: Result) {
    when (result) {
        is Result.Success -> println("Success: ${result.data}")
        is Result.Error -> println("Error: ${result.message}")
        Result.Loading -> println("Loading...")
    }
}
```

---

### Sealed Classes in Android

Sealed classes are perfect for modeling **UI state** in Android:

**Example:**

```kotlin
sealed class UiState {
    object Loading : UiState()
    data class Success(val data: List<String>) : UiState()
    data class Error(val message: String) : UiState()
}
```

---

### Inline Classes

An **inline class** is a wrapper around a single value with no runtime overhead.

**Example:**

```kotlin
@JvmInline
value class Password(private val s: String)
```

---

### Companion Objects

A **companion object** is a special object declared inside a class, similar to static members in Java.

**Example:**

```kotlin
class MyClass {
    companion object {
        const val MY_CONSTANT = "Hello"
        fun create(): MyClass = MyClass()
    }
}
```

---

### Singleton Class

A **Singleton** in Kotlin is created using the `object` keyword.

**Example:**

```kotlin
object MySingleton {
    fun doSomething() {
        println("Singleton method called.")
    }
}

MySingleton.doSomething()
```

---

### Extension Functions

**Extension functions** add new functionality to existing classes without inheritance.

**Example:**

```kotlin
fun String.addExclamation(): String {
    return this + "!"
}

val result = "hello".addExclamation() // "hello!"
```

---

### Scope Functions (let, run, with, also, apply)

| Function | Context Object | Return Value | Common Use Cases |
|----------|---------------|--------------|------------------|
| `let`    | `it`          | Lambda result | Null safety, local scope |
| `run`    | `this`        | Lambda result | Object initialization with computation |
| `with`   | `this`        | Lambda result | Multiple calls on an object |
| `also`   | `it`          | Context object | Side effects |
| `apply`  | `this`        | Context object | Object configuration |

---

### apply Scope Function

The `apply` function configures an object and returns the object itself.

**Example:**

```kotlin
val person = Person().apply {
    name = "Alice"
    age = 30
}
```

---

### let Scope Function

The `let` function performs actions on a non-null object and returns the lambda result.

**Example:**

```kotlin
val result = name?.let {
    println("The name is $it")
    it.length
}
```

---

### apply vs with

- `apply` is an extension function that returns the object itself
- `with` is a non-extension function that returns the lambda result

---

## 📦 Collections & Data Operations

### Collections

Kotlin separates **mutable** and **immutable** collections:

- **`List`:** Ordered collection with duplicates allowed
- **`Set`:** Unique elements with no defined order
- **`Map`:** Key-value pairs

**Example:**

```kotlin
val numbers = listOf(1, 2, 3)
val uniqueNumbers = setOf(1, 2, 2) // [1, 2]
val nameMap = mapOf("Alice" to 30)
```

---

### List vs Array

| Feature | **List** | **Array** |
|---------|----------|-----------|
| **Mutability** | Immutable (`List`) or mutable (`MutableList`) | Mutable with fixed size |
| **Size** | Dynamic | Fixed |
| **Performance** | Slower due to overhead | Faster for primitives |
| **Use Case** | General-purpose collections | Performance-critical scenarios |

---

### Removing Duplicates from an Array

**Example:**

```kotlin
val numbers = arrayOf(1, 2, 3, 2, 1)
val unique = numbers.distinct().toTypedArray()
// or
val uniqueSet = numbers.toSet().toTypedArray()
```

---

### associateBy

Transforms a collection into a Map using a key selector.

**Example:**

```kotlin
data class Person(val id: Int, val name: String)
val people = listOf(Person(1, "Alice"), Person(2, "Bob"))
val peopleByName = people.associateBy { it.name }
```

---

### partition Filtering Function

Splits a collection into two lists based on a predicate.

**Example:**

```kotlin
val numbers = listOf(1, 2, 3, 4, 5, 6)
val (even, odd) = numbers.partition { it % 2 == 0 }
```

---

## ☕ Java Interoperability

### @JvmStatic Annotation

Exposes a companion object function as a true static method in Java.

**Example:**

```kotlin
class MyClass {
    companion object {
        @JvmStatic
        fun myStaticMethod() {
            println("Static method")
        }
    }
}
```

---

### @JvmField Annotation

Exposes a Kotlin property as a public field in Java.

**Example:**

```kotlin
class MyClass {
    @JvmField
    val myField = "Value"
}
```

---

### @JvmOverloads Annotation

Generates overloaded methods for functions with default parameters.

**Example:**

```kotlin
@JvmOverloads
fun greet(name: String = "World", greeting: String = "Hello") {
    println("$greeting, $name!")
}
```

---

### Java Static Methods Equivalent

In Kotlin, use **companion objects** or **top-level functions**:

```kotlin
// Top-level function
fun isEven(n: Int) = n % 2 == 0

// Companion object
class Utils {
    companion object {
        fun helper() { }
    }
}
```

---

## 🌊 Kotlin Coroutines

### Coroutines

**Coroutines** are lightweight threads for asynchronous programming. They can suspend execution without blocking threads.

**Example:**

```kotlin
fun main() = runBlocking {
    launch {
        delay(1000L)
        println("World!")
    }
    println("Hello,")
}
```

---

### Suspending vs Blocking

- **Suspending:** Pauses execution without blocking the thread
- **Blocking:** Holds the thread until completion

**Example:**

```kotlin
// Suspending - doesn't block thread
suspend fun fetchData() {
    delay(1000)
}

// Blocking - blocks thread
fun blockingFunction() {
    Thread.sleep(1000)
}
```

---

### launch vs async

| Feature | `launch` | `async` |
|---------|----------|---------|
| **Returns** | `Job` | `Deferred<T>` |
| **Purpose** | Fire-and-forget | Return a result |
| **Usage** | Side effects | Parallel computation |

**Example:**

```kotlin
val job = launch { /* do work */ }
val deferred = async { /* return value */ }
val result = deferred.await()
```

---

### Dispatchers in Kotlin Coroutines

- **`Dispatchers.Main`:** UI thread
- **`Dispatchers.IO`:** I/O operations
- **`Dispatchers.Default`:** CPU-intensive work
- **`Dispatchers.Unconfined`:** No specific thread

---

### coroutineScope vs supervisorScope

- **`coroutineScope`:** Fails all children if one fails
- **`supervisorScope`:** Isolates failures to individual children

---

### Coroutine Scope

Defines the lifecycle of coroutines:

```kotlin
val scope = CoroutineScope(Dispatchers.Default)
scope.launch { /* coroutine */ }
```

---

### Coroutine Context

Collection of elements defining coroutine behavior:

```kotlin
val context = Job() + Dispatchers.IO + CoroutineName("MyTask")
```

---

### Coroutine Scopes in Android

- `viewModelScope`: Tied to ViewModel lifecycle
- `lifecycleScope`: Tied to Activity/Fragment lifecycle

---

### runBlocking in Coroutines

Blocks the current thread until coroutine completes:

```kotlin
fun main() = runBlocking {
    delay(1000)
    println("Done")
}
```

---

### Structured Concurrency

Parent-child hierarchy ensuring proper lifecycle management:

- Parent cancellation cancels all children
- Parent waits for all children to complete

---

### withContext

Changes coroutine context for a block of code:

```kotlin
suspend fun fetchData() {
    val data = withContext(Dispatchers.IO) {
        // IO operation
        api.getData()
    }
    // Back to original context
}
```

---

### Thread.sleep() vs delay()

- `Thread.sleep()`: Blocks thread
- `delay()`: Suspends coroutine without blocking thread

---

### Coroutine Timeouts

```kotlin
val result = withTimeoutOrNull(1300L) {
    // Operation that might timeout
    "Success"
} ?: "Timeout"
```

---

### Combining Coroutine Results

```kotlin
coroutineScope {
    val user = async { fetchUser() }
    val posts = async { fetchPosts() }
    
    val userData = user.await()
    val userPosts = posts.await()
}
```

---

### Job in Coroutines

Represents coroutine lifecycle:

```kotlin
val job = launch { /* work */ }
job.cancel() // Cancel the coroutine
job.join()   // Wait for completion
```

---

### job.cancel() vs scope.cancel()

- `job.cancel()`: Cancels single coroutine
- `scope.cancel()`: Cancels all coroutines in scope

---

### Exception Handling in Coroutines

```kotlin
val handler = CoroutineExceptionHandler { _, exception ->
    println("Caught: ${exception.message}")
}

scope.launch(handler) {
    throw Exception("Error")
}
```

---

### Exception in Unawaited async

Exceptions in `async` are stored until `await()` is called:

```kotlin
val deferred = async { throw Exception() }
// Exception thrown here:
deferred.await()
```

---

### Debounce with Coroutines

```kotlin
fun <T> debounce(
    waitMs: Long = 300L,
    scope: CoroutineScope,
    action: suspend (T) -> Unit
): (T) -> Unit {
    var job: Job? = null
    return { param: T ->
        job?.cancel()
        job = scope.launch {
            delay(waitMs)
            action(param)
        }
    }
}
```

---

### Coroutines in Series and Parallel

**Series:**
```kotlin
val result1 = doFirst()
val result2 = doSecond(result1)
```

**Parallel:**
```kotlin
coroutineScope {
    val d1 = async { doFirst() }
    val d2 = async { doSecond() }
    val results = awaitAll(d1, d2)
}
```

---

### yield in Coroutines

Yields execution to other coroutines:

```kotlin
launch {
    repeat(3) {
        println("Task $it")
        yield() // Give other coroutines a chance
    }
}
```

---

### Callback to Coroutines in Kotlin

Convert callback-based APIs to suspend functions:

```kotlin
suspend fun fetchData(): Result = suspendCoroutine { continuation ->
    api.fetchData { result ->
        continuation.resume(result)
    }
}
```

---

### Retrofit with Kotlin Coroutines

```kotlin
interface ApiService {
    @GET("users/{id}")
    suspend fun getUser(@Path("id") id: String): User
}

// Usage
val user = apiService.getUser("123")
```

---

### Room Database with Kotlin Coroutines

```kotlin
@Dao
interface UserDao {
    @Query("SELECT * FROM users")
    suspend fun getAllUsers(): List<User>
    
    @Insert
    suspend fun insertUser(user: User)
}
```

---

### Unit Testing ViewModel with Kotlin Coroutines and LiveData

```kotlin
@Test
fun testViewModel() = runTest {
    val viewModel = MyViewModel(mockRepository)
    viewModel.loadData()
    
    assertEquals(expectedState, viewModel.state.value)
}
```

---

## 🌊 Kotlin Flow API

### Flow Builder, Operator, Collector

- **Builder:** Creates a Flow
- **Operators:** Transform the Flow
- **Collector:** Consumes the Flow

```kotlin
flow { emit(1) }        // Builder
    .map { it * 2 }     // Operator
    .collect { }        // Collector
```

---

### flowOn, Dispatchers

Changes the dispatcher for upstream operations:

```kotlin
flow { emit(fetchData()) }
    .flowOn(Dispatchers.IO)
    .collect { } // Runs on original context
```

---

### Operators

| Operator | Description |
|----------|-------------|
| `filter` | Filters values |
| `map` | Transforms values |
| `zip` | Combines two flows |
| `flatMapConcat` | Sequential processing |
| `flatMapLatest` | Cancels previous on new emission |
| `debounce` | Delays emissions |
| `distinctUntilChanged` | Filters consecutive duplicates |
| `retry` | Retries on failure |

---

### Terminal Operators

Start Flow collection:

- `collect()`: Collects all values
- `first()`: First value
- `toList()`: Converts to list
- `single()`: Single value
- `launchIn()`: Non-suspending collection

---

### Cold Flow vs Hot Flow

| Feature | Cold Flow | Hot Flow |
|---------|-----------|----------|
| **Start** | On collection | Immediately |
| **State** | Independent streams | Shared stream |
| **Example** | `flow { }` | `StateFlow`, `SharedFlow` |

---

### StateFlow, SharedFlow, callbackFlow, channelFlow

- **`StateFlow`:** Hot flow with single latest value
- **`SharedFlow`:** Configurable hot flow for events
- **`callbackFlow`:** Convert callbacks to Flow
- **`channelFlow`:** Complex emission patterns

---

### stateIn vs shareIn in Flow

- **`stateIn`:** Creates StateFlow from cold flow
- **`shareIn`:** Creates SharedFlow from cold flow

```kotlin
val stateFlow = flow.stateIn(
    scope = viewModelScope,
    started = SharingStarted.Lazily,
    initialValue = default
)
```

---

### flatMapConcat, flatMapMerge, and flatMapLatest

- **`flatMapConcat`:** Sequential processing
- **`flatMapMerge`:** Concurrent processing
- **`flatMapLatest`:** Cancels previous, processes latest

---

### collect vs collectLatest

- **`collect`:** Processes each value sequentially
- **`collectLatest`:** Cancels previous processing for new values

---

### Exception Handling in Flow

```kotlin
flow { emit(value) }
    .catch { e ->
        println("Error: ${e.message}")
        emit(fallbackValue)
    }
    .collect()
```

---

### Unit Testing with Flow

```kotlin
@Test
fun testFlow() = runTest {
    val flow = repository.dataFlow
    val results = flow.take(3).toList()
    assertEquals(expected, results)
}
```

---

## 📱 Android Development

### Android Push Notification Flow using FCM

1. **Registration:** App gets FCM token
2. **Token Upload:** Send token to app server
3. **Message Creation:** Server creates notification payload
4. **Sending:** Server sends to FCM
5. **Delivery:** FCM delivers to device
6. **Reception:** App handles based on state (foreground/background)

---

### What is a ViewModel and how is it useful?

`ViewModel` stores and manages UI-related data in a lifecycle-aware way:

- Survives configuration changes
- Separates UI logic from business logic
- Prevents memory leaks

```kotlin
class MyViewModel : ViewModel() {
    val data = MutableLiveData<String>()
}
```

---

### Why is it recommended to use only the default constructor to create a Fragment?

Android system uses reflection to recreate fragments after configuration changes. It can only call the default constructor. Use `arguments` Bundle for passing data:

```kotlin
companion object {
    fun newInstance(data: String) = MyFragment().apply {
        arguments = bundleOf("key" to data)
    }
}
```

---

### Why do we need to call setContentView() in onCreate() of Activity class?

`setContentView()` inflates the layout XML and attaches it to the activity's window. Without it, the activity has no UI to display.

---

### When only onDestroy is called for an activity without onPause() and onStop()?

During process death when the system kills the app for memory. The system doesn't call lifecycle methods in order, just terminates the process.

---

### singleTask launchMode in Android

Creates at most one instance of the activity. If it exists, brings it to top and calls `onNewIntent()`:

```xml
<activity android:launchMode="singleTask" />
```

---

### What is Multidex in Android?

Allows apps to exceed the 65,536 method limit by splitting into multiple DEX files:

```gradle
android {
    defaultConfig {
        multiDexEnabled true
    }
}
```

---

### Is it possible to force Garbage Collection in Android?

No, you can only suggest it:

```kotlin
System.gc() // Just a hint, not guaranteed
```

Focus on proper lifecycle management instead.

---

## 🌍 Cross-Platform

### Kotlin Multiplatform

Share code across platforms while keeping UI native:

- **Common Module:** Business logic, networking, data
- **Platform-Specific:** UI and platform APIs
- **expect/actual:** Platform-specific implementations

```kotlin
// Common
expect fun platformName(): String

// Android
actual fun platformName(): String = "Android"

// iOS
actual fun platformName(): String = "iOS"
```
