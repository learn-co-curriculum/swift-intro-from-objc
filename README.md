# Swift — Introduction From Objective-C

## Introduction

While Swift is comparatively a young language, having only been publicly announced in June of 2014, the foundational work towards adopting it was begun in 2010 when Apple attracted the efforts of [Chris Lattner](https://en.wikipedia.org/wiki/Chris_Lattner), the [creator of LLVM](http://nondot.org/sabre/). Changes to the canonical 30-year-old programming language Objective-C were incorporated to pave the way towards the transition to its replacement. These included the additions of Automatic Reference Counting (ARC) and closures, among other improvements to the Objective-C language. The goal, however, was to create a new language with modern programming capabilities and syntax. 

##### Statically Typed

And indeed, many aspects of developing with Swift are cleaner and quicker. It is a strongly-typed (or "statically-typed") language that attempts to move errors out of the run-time phase and into the compile-time phase; a move with the intent of making deployed code "safer", but with the effect of handling null reference pointers in a different way.

##### Syntax & Foundation

What Swift really changes in iOS development is the syntax with which code is written, and provides a new Foundation framework. Development with Swift uses the same Xcode IDE as Objective-C development. It incorporates elements of functional programming, moving away from the only-object-oriented paradigm of Objective-C. Swift holds libraries and projects in distinct "modules", altogether eliminating the need for class prefixes and header files.

##### Objective-C Interoperability

Swift can interface with classes written in Objective-C through a process called bridging. In fact, changes to the Objective-C language have been shipped with new versions of Xcode in order to improve compatibility with Swift and streamline the bridging process. This means that existing applications written in Objective-C can be migrated to Swift one class at a time, and that third-party libraries written in Objective-C can still be used in Swift-based applications.

##### Cocoa & Cocoa Touch

The extensive library of framework classes used in iOS development (known as Cocoa and Cocoa Touch) are actually written in C, but they now include interfaces written for use with Swift. This means that the Apple libraries that you're used to using are still available in Swift and work in essentially the same ways.

##### Apple's Introduction of Swift

In its efforts to get developers to adopt Swift, Apple has already articulated a lot of information about its new language. Take the time now to:

1. Read [Apple's Swift Overview](https://developer.apple.com/swift/).

2. Read the [About Swift](https://developer.apple.com/library/prerelease/ios/documentation/Swift/Conceptual/Swift_Programming_Language/index.html#//apple_ref/doc/uid/TP40014097-CH3-ID0) page of Apple's *The Swift Programming Language* Manual.

3. Glance through the [Wikipedia page about Swift](https://en.wikipedia.org/wiki/Swift_(programming_language)) for information on its short history.

4. Read some of [these answers on Quora](https://www.quora.com/Why-would-Apple-introduce-new-programming-languages-e-g-Swift-instead-of-embracing-an-existing-one) about why Apple chose to develop Swift.

### The Purpose Of These Lessons

These lessons are an overview of how to write Swift implementations for application software with **no prior exposure to Swift**. 

While Apple's reference documentation on Swift is overall quite excellent, it is voiced towards experienced developers with a solid understanding of computer science concepts and aimed towards precise exposition of how the language works, sometimes discussing it on a very low level. It can be difficult for unseasoned programmers to distill the necessary information about *how to use* Swift for a given step in an application.

These lessons offer a guided journey of learning the fundamentals of composing software in Swift: the language's syntax, its foundation framework, and the new programming concepts made available to iOS development when using Swift.

### Prerequisites

These lessons assume a prior knowledge of:

  * using bash, git, and GitHub for managing source control; 
  * using the Xcode IDE and its various toolsets including Apple's Reference Documentation; and
  * fundamental programming concepts learned from proficiency in another C-family programming language (which may or may not be Objective-C), including:
     * syntax, variables, and operators,
     * strings, collections, and flow control,
     * scope and visibility,
     * running tests and debugging, and
     * Object Oriented Programming including classes, methods, properties, and inheritance.

*Specific knowledge of Objective-C is helpful but not necessary, except for the material regarding Objective-C bridging.* 

*Experience using Cocoa and Cocoa Touch are helpful but not necessary.*

*Knowledge of low-level computer science and language-agnostic algorithmic thinking is not necessary.*

##### Xcode 7.1 & Swift 2.1 (released Oct 21, 2015)

These lessons are written for the latest version of the Swift programming language (2.1) that is included in Xcode 7.1 and later. It is strongly recommended that you update to Xcode 7.1 or later for working on these labs. If you are unsure which version of Xcode you have installed, select `Xcode -> About Xcode` from the taskbar when Xcode is the active application on your machine.

##### System Recommendations

Xcode 7.1 is available to all MacIntosh computers running OS 10.10 Yosemite and OS 10.11 El Capitan. You must have a machine running one of these two versions of OS X in order to work with Swift 2.1.

While some machines as old as 2009 may be able to download Xcode 7.1, they may not perform well when running a scheme. It is recommended to use a MacIntosh with a Core i5 or i7 dual-core processor (or better), which has been common to MacIntosh computers since 2011. A capacity of 8GB of RAM is also recommended but not strictly necessary.

If you are uncertain of your machine's specifications, select `About This Mac` from the Apple logo in the taskbar.



