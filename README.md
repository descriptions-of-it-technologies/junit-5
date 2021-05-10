# JUnit 5.





## Contents at a Glance.
* [About](#about)
* [Documentation.](#documentation)
* [Unit Tests. Unit Testing. Code written to test code under test.](#unit-tests-unit-testing-code-written-to-test-code-under-test)
* [JUnit 5 Modules.](#junit-5-modules)
* [JUnit Annotations.](junit-5-annotaions.md)
* [JUnit Assertion Lambdas.](#junit-assertion-lambdas)
* [JUnit Test Dependency Injection. Parameter Resolver.](#junit-test-dependency-injection-parameter-resolver)
* [Help](#help)





## About.





## Documentation.
* [JUnit 5.](https://junit.org/junit5/)





## Unit Tests. Unit Testing. Code written to test code under test.
* Designed to test specific section of code.
* Percentage of lines of code tested is code coverage.
* Ideal coverage is in the 70-80% range.
* Should be 'unity' and execute very fast.
* Should not have external dependencies.
* ie no database, no Spring context, etc.





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
  
  
  
  
  
## Pros.
*  JUnit 5 utilizes Java 8 features like lambdas for lazy evaluation.




## Cons.





## Migration JUnit 4 to JUnit 5.
* Replace dependencies - JUnit 4 uses a single dependency. JUnit 5 has additional dependencies for migration support and JUnit Vintage engine.
* Replace annotations - Some JUnit 5 annotations are the same as JUnit 4. Some new ones replace the old ones, and function a little different.
* Replace testing classes and methods - Assertions and assumptions have been moved to new classes. Method argument order is different in some cases.
* Replace runners and rules with extensions	JUnit 5 - has a single extension model instead of runners and rules. This step could take more time than the others.


## 

| JUnit 4              | JUnit 5                |
| -------------------- | ---------------------- |
| @Test                | @Test                  |
| @Before              | @BeforeEach            |
| @After               | @AfterEach             |
| @BeforeClass         | @BeforeAll             |
| @AfterClass          | @AfterAll              |
| @Ignore              | @Disable               |
| @Category            | @Tag                   |
|                      |                        |





## Useful links.
* [Migrating From JUnit 4 to JUnit 5: A Definitive Guide](https://www.arhohuttunen.com/junit-5-migration/)





## Help.
