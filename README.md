## Corretto JDK

Amazon Corretto is a no-cost, multiplatform,
production-ready distribution of the Open Java Development Kit (OpenJDK).
Corretto is used internally at Amazon for production services.
With Corretto, you can develop and run Java applications 
on operating systems such as Linux, Windows, and macOS.

This repository is used to track [OpenJDK upstream tip](https://github.com/openjdk/jdk). 
Please look at the branches section for more information on Feature Releases. 

Documentation is available at [https://docs.aws.amazon.com/corretto](https://docs.aws.amazon.com/corretto).

### Licenses and Trademarks

Please read these files: "LICENSE", "ADDITIONAL_LICENSE_INFO", "ASSEMBLY_EXCEPTION", "TRADEMARKS.md".

### Branches

_develop-jdk15_
: The default branch. The branch that consumes development and patches to upstream jdk15. Corretto 15 builds are generated from this branch. 

_develop_
: It absorbs active development contributions from forks or topic branches via pull requests that pass smoke testing and are accepted.

_upstream-jdk15_
: The branch is similar to master at [openjdk/jdk15](https://github.com/openjdk/jdk15). This branch merges into develop-jdk15.

_upstream_
: The branch is similar to master at [openjdk/jdk](https://github.com/openjdk/jdk). This branch merges into develop.


### OpenJDK Readme 
```

Welcome to the JDK!
===================

For build instructions, please see either of these files:

  * doc/building.html   (html version)
  * doc/building.md     (markdown version)

See https://openjdk.java.net/ for more information about
the OpenJDK Community and the JDK.
```