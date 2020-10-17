# JUnit 5 Annotations.





## Contents at a Glance.
* [About](#about)
* [Documentation.](#documentation)
* [Annotations.](#annotations)
* [Useful links.](#useful-links)
* [Help](#help)





## About.





## Documentation.





## Annotations.

| Annotation                                            | Description                                                                                |
| ----------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| @Test                                                 | Marks a method as a test method.                                                           |
| @ParametrizedTest                                     | Makes method as a parametrized test.                                                       |
| @RepeatedTest                                         | Repeat test N times.                                                                       |
| @TestFactory                                          | Test Factory method for dynamic tests.                                                     |
| @TestInstance                                         | Used to configure test instance lifecycle.                                                 |
| @TestTemplate                                         | Create a template to be used by multiple test cases.                                       |
| @DisplayName                                          | Human friendly name for test.                                                              |
| @BeforeEach                                           | Method to run before each test case.                                                       |
| @AfterEach                                            | Method to run each each test case.                                                         |
| @BeforeAll                                            | Static method to run before all test cases in current class.                               |
| @AfterAll                                             | Static method to run after all test cases in current class.                                |
| @Nested                                               | Create a nested test class.                                                                |
| @Tag                                                  | Declare 'tags' for filtering tests.                                                        |
| @Disabled                                             | Disable test or test class.                                                                |
| @ExtendWith                                           | Used to register extension.                                                                |
| @TestPropertySource                                   |                                                                                            |
| @ExtendWith(SpringExtension.class)                    | SpringExtension introduced in Spring 5, is used to integrate Spring TestContext with JUnit 5 Jupiter Test. SpringExtension is used with JUnit 5 Jupiter @ExtendWith annotation as following. |
| @ContextConfiguration                                 |                                                                                            |
| @ExtendWith(MockitoExtension.class)                   | If you just want to involve Mockito and don't have to involve Spring, for example, when you just want to use the @Mock / @InjectMocks annotations. |
|                                                       |                                                                                            |





## Useful links.





## Help.





