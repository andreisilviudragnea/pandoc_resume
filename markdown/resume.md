Andrei Silviu Dragnea
=====================

Education
---------

2013-2017
:   **BSc, Computer Science and Engineering**; Faculty of Automatic
    Control and Computers, Politehnica University of Bucharest (Bucharest)

    *Thesis title: Automatic Recursion Removal in Java (as an [Intellij Plugin](https://plugins.jetbrains.com/plugin/10295-remove-recursion-inspection))*

Experience
----------

* Good knowledge of Operating Systems internals
* Proficient in C, C++, Kotlin, Java and Python
* Middle level in Rust
* Passionate about type systems, static analysis and programming language design

September 2017 - December 2017
: **Software Developer at Instacar**
I was mainly responsible for implementing a TCP server communicating with some devices capable of remote car control, which used a proprietary binary protocol. I have also been responsible for integrating the backend with Amazon Cloudwatch. Because of the rather poorly maintained codebase, I introduced type hints in the code and I have also developed a Pycharm [plugin](https://plugins.jetbrains.com/plugin/10194-python-enhancements) for automatic detection and removal of dead code, provided the code base had enough type hints specified in order to refactor the code reliably. The source is available [here](https://github.com/andreisilviudragnea/PythonDCE).

January 2018 - February 2018
: **Linux Embedded Developer at Enea**
I was responsible for developing the firmware of a simulator for a smoke detectors network.

I am an active contributor to the [Intellij Platform](https://github.com/JetBrains/intellij-community/pull/697) and an aspiring contributor to LLVM, the Rust compiler and the Linux kernel. I generally inspire myself and contribute to open source projects which share my values for code quality.

Bachelor thesis
---------------

Recursion Removal in Java
:   Recursion can rapidly exhaust the stack space of a program and it can
    be replaced with iteration by simulating the stack in the user program.
    I have implemented a custom *inspection* for Intellij IDEA (which basically extends the *Tail Recursion* inspection from the *Performance Group*), which automatically detects recursive methods in Java code and replaces them with equivalent iterative versions of the code. The algorithm is rather complex and it is described [here](https://github.com/andreisilviudragnea/remove-recursion-inspection/blob/master/thesis/thesis.pdf). The inspection is implemented in Kotlin and the source is available [here](https://github.com/andreisilviudragnea/remove-recursion-inspection).

> [Github account](https://github.com/andreisilviudragnea)\
> <andreisilviudragnea@gmail.com> • +40 746 337 605 • 24 years old\
> Bucharest, Romania
