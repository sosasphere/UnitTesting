# UnitTesting
JUnit 5 and Mockito Notes

This repository is a collection of commonly used unit testing methods

Annotations:
- @DisplayName("Test Name and Description)
- 
- @Test: indicated to Spring Context that the methods is a test method
- 

Terms:

- assertTrue(condition)
- assertFalse(condition)
- assertNull
- assertNotNull
- assertThat
- assertEquas(expected, actual)
- assertAll(
    () -> assertEquals(expected1, actual1),
    () -> assertEquals(expected2, actual2)
  );
- assertThrows(Exception.class, () -> {
  });
