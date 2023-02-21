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

* Expert in refactoring and decoupling complex systems into self-contained and loosely-coupled components
* Intellij plugin [developer](https://plugins.jetbrains.com/plugin/10194-python-enhancements)
* [Spring](https://github.com/spring-projects/spring-framework) and [Spring Boot](https://github.com/spring-projects/spring-boot) framework expert
* Async programming expert: [Project Reactor](https://github.com/reactor/reactor-core) from Spring,
 [Kotlin coroutines](https://github.com/Kotlin/kotlinx.coroutines),
 [cats-effect](https://github.com/typelevel/cats-effect) and [zio](https://github.com/zio/zio) from Scala,
 Rust [async](https://rust-lang.github.io/async-book/) programming
* Experience in profiling JVM applications and optimizing runtime performance and resource usage 
using [VisualVM](https://visualvm.github.io/)
* Open source contributor to
  [Docker](https://github.com/docker/docs/pull/15477),
  [mockito](https://github.com/mockito/mockito/pulls?q=is%3Apr+author%3Aandreisilviudragnea+is%3Aclosed),
  [intellij-kotlin](https://github.com/JetBrains/intellij-kotlin/pull/69),
  [intellij-community](https://github.com/JetBrains/intellij-community/pull/697),
  [reactor-core](https://github.com/reactor/reactor-core/pull/1969),
  [reactor-netty](https://github.com/reactor/reactor-netty/issues/628),
  [netty](https://github.com/netty/netty/issues/8915),
  [spring-framework](https://github.com/spring-projects/spring-framework/pull/24977),
  Scala [kubernetes-client](https://github.com/joan38/kubernetes-client/pull/106),
  [Renovate](https://github.com/renovatebot/renovate/pull/14566)
* Proficient in Java, Kotlin, Scala, Rust, C and Python
* Build system expert: Maven, Gradle, Earthly, Docker, sbt. Reduced build times of Scala projects significantly.
* Author of an automatic Git [rebaser](https://github.com/andreisilviudragnea/rebaser) written in Rust
* Passionate about static analysis and automatic refactoring in Java, Kotlin, Scala and Rust
* Working on a [converter](https://github.com/andreisilviudragnea/reactor-to-kotlin) from Java reactive code to Kotlin coroutines
* Experience with enterprise identity protocols and frameworks, such as OAuth2, SCIM2, SAML
* Worked with Kafka, Apache Spark, Docker, Kubernetes, Envoy, Grafana, Prometheus, AWS EC2, S3, Route53, Cloudwatch, 
Splunk, Datadog, NewRelic, Azure Active Directory, Jenkins, ScalaTest, ScalaMock, JUnit, TestNG, Renovate, Dependabot,
Cassandra, MySQL.
* Good knowledge of Operating Systems internals and how async frameworks are implemented
* Promoter of the [clean tests](https://medium.com/@andreisilviudragnea/towards-cleaner-pure-tests-20f1356dee4c) paradigm

May 2021 - Present
: **Software Engineer at Adobe (Media Analytics team)**
I work on a performance-sensitive Video Analytics system written in Scala, which handles 2.6 million of events per 
second at peak traffic. I optimized the runtime performance by correctly handling blocking calls in the non-blocking 
events collecting system. The event ingestion system writes the events in Kafka topics, from where an Apache Spark job 
processes them and generates reports. I implemented an event filtering mechanism for dropping traffic from 
customers not paying a subscription, in order to reduce costs in our infrastructure. I also re-wrote the event ingestion
system in Rust, resulting into 2.6x CPU usage and 50x memory usage reduction.

March 2018 - May 2021
: **Software Engineer at Adobe (Identity Management Services team)**
I was part of the Identity Management Services team. I worked on implementing the server side of the SCIM2 
protocol over a Spring 5 reactive stack. I developed a thin wrapper over Mockito and Spring TestContext
framework in order to promote writing [clean tests](https://medium.com/@andreisilviudragnea/towards-cleaner-pure-tests-20f1356dee4c).
I introduced Kotlin and coroutines to our team, as a developer-friendly alternative for writing non-blocking code.
I made major software architectural changes by using smart refactoring tricks, resulting in a simpler system design.

September 2017 - December 2017
: **Software Engineer at Instacar**
I implemented a TCP server over a proprietary binary protocol for remote car control. I recompiled the Linux kernel with
custom TCP settings in order to compensate for a faulty TCP implementation on the devices used for remote car control.
I introduced type hints to the Python 3 codebase and I developed a Pycharm [plugin](https://plugins.jetbrains.com/plugin/10194-python-enhancements)
for dead code elimination.

I always strive the find the simplest solution possible to a problem. I proactively fix problems
from any software project that I encounter, whether it is internal to my company, or an open source project.

> <https://github.com/andreisilviudragnea>\
> <andreisilviudragnea@gmail.com>
