**URLify:** Write a method to replace all spaces (" ") in
 a character buffer (array) with "%20". You may assume
 that the buffer has sufficient space at the end to hold
 the additional characters, and that you are given the "true"
 size of the buffer (which is different from the length or capacity
 of the buffer).

 **Constraint:** perform the operation in place (in the existing
 buffer), without creating a new or temporary buffer or string.

 **Example**
```
            buffer                             size
            -------------------------------    ----
 Input      Hello, world!                      13
 Output     Hello,%20world!                    15

 Input      Dr Martin Luther King              21
 Output     Dr%20Martin%20Luther%20King        27
```

 **Learning Objectives:**
  * To practice an interview question.
  * To recognize the difference between size and length when working
    with a buffer (similar to how a resizable ArrayList, and/or a
    StringBuilder's internals would work).
  * To create and implement an algorithm to manipulate contents of an array.
  * To analyze the runtime performance of the algorithm.

 **Source:**
 Gayle Laakmann McDowell. 2016. *Cracking the Coding Interview (6th ed.)*
 CareerCup, Palo Alto, CA.
