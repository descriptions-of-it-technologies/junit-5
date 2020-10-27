# JUnit 5.





## Contents at a Glance.
* [About](#about)
* [Documentation.](#documentation)
* [JUnit 5 Modules.](#junit-5-modules)
* [JUnit Annotations.](junit-5-annotaions.md)
* [JUnit Assertion Lambdas.](#junit-assertion-lambdas)
* [JUnit Test Dependency Injection. Parameter Resolver.](#junit-test-dependency-injection-parameter-resolver)
* [Help](#help)





## About.





## Documentation.
* [JUnit 5.](https://junit.org/junit5/)





## JUnit 5 Modules.
* JUnit Platform - The foundation for launching testing frameworks on the JVM. Allows test to be run for a Console Launcher,
  or build tools such a Maven and Gradle.
* JUnit Jupiter - Programming model from writing tests and extensions to JUnit.
* JUnit Vintage - Provides a test engine for running JUnit 3 and JUnit 4 tests.





## JUnit Assertion Lambdas.
* JUnit 5 incorporate support of lambdas in assertions.
* Grouped Assertions - all assertions run in block, all failure reported.
* Dependent Assertion - allow for blocks of grouped assertions.
* Expected exceptions are tested with assertThrows lambda expression.
* Timeouts are tested with assertTimeout lambda expression.





## JUnit Test Dependency Injection. Parameter Resolver.
* JUnit 5 Defines a Parameter Resolver API to resolve parameters at runtime.
* Allows JUnit to inject parameters into test methods.
* While extensible, there are 3 built in resolvers:
  * TestInfo - Provides information about the test name, method, test class, test tags.
  * RepetitionInfo - Provides Information about the test repetition.
  * TestReporter - Allows you to publish runtime information for test reporting.
  
  
  
  
  
## Help.
