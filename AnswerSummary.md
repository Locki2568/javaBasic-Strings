# Java Basic - Strings
## Boolean Operation test
 1.What is the knowledge point of the test? Where is the official document to the knowledge point?
- The point is about [Optional Class](https://www.tutorialspoint.com/java8/java8_optional_class.htm)
- [String is immutable](https://stackoverflow.com/questions/8798403/string-is-immutable-what-exactly-is-the-meaning)
- [The StringBuilder Class](https://docs.oracle.com/javase/tutorial/java/data/buffers.html)
- [Convert a char to int](https://stackoverflow.com/questions/46343616/how-can-i-convert-a-char-to-int-in-java/46343671)
- [Converting Between Unicode Characters and Strings](https://www.oreilly.com/library/view/java-cookbook/0596001703/ch03s07.html)
- [Reverse a string in Java](https://stackoverflow.com/questions/7569335/reverse-a-string-in-java)

2.Why the test failed at first?
- It's because the expected result is originally set to 0 or some pre-fixed value while "assertEquals()/assertThrows()" compare the expected and the actual result and output a Boolean as the comparison result. 

3.Why you corrected the test that way?
- So that the expected result should be matched to the actual result which is stated in each unit test

4.Do you have further questions on this knowledge point?
 - Should be okay
