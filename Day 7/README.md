# Python File and Exception Handling

🚀 Day 7 of our Data Science Adventure!

Today, we're diving deeper into the world of Python, learning about file and exception handling. Like a skilled navigator, we'll chart our course through the twists and turns of file operations and exception handling, ensuring our code is strong and reliable. With each line, we're not just coding; we're building a safety net for our data, protecting it from the unknown and the unexpected. So get ready for an exciting journey as we master the art of file and exception handling in our 75-day challenge 👩‍💻🔍✨

## Table of Contents

### File Handling

* Types of data used for I/O
* Text
* Binary
* I/O operations on file:
  * Open
  * Read
  * Write
  * Close
* Different ways to perform this operation:
  * 1. If the file is not present
  * 2. If the file is already present
  * 3. Writing multiple lines
  * 4. Reading from files
  * 5. Reading entire file using deadline
  * 6. Using context manager (with):
    * with keyword closes the file as soon as the usage is over.
    * While using the with a keyword you don't have to use f.close()
  * 7. seek and tell function
* Problems with working text mode:
  * You can't work with binary files like images.
  * It is not suitable for other data types like int, float, list, and tuple.

### Serialization & Deserialization

* Serialization is the process of converting an object into a format that can be stored or transmitted, while deserialization is the reverse process of converting the serialized data back into an object.
* Drawbacks of JSON format:
  * JSON supports a limited set of data types (e.g., strings, numbers, lists, dictionaries), which means certain Python objects like sets and tuples cannot be directly serialized.
  * JSON may lose precision for floating-point numbers.
  * Deserializing data from untrusted sources can be a security risk, as it may lead to code injection vulnerabilities.
* Pickling & unpickling:
  * Pickling is the process of converting a Python object into a byte stream, and unpickling is the reverse process of converting the byte stream back into a Python object.
  * The pickle module in Python is used for serializing and deserializing Python objects to maintain the functionality.
* Pickle Vs JSON:
  * Pickle lets you store data in binary format to maintain functionality.
  * JSON let's user store data in a human-readable format by default, it is a dictionary.

### Exception Handling

* Exception handling in Python allows you to handle errors gracefully and maintain the normal flow of the program.
* It uses try, except, else, and finally blocks to catch and handle exceptions.
* Exception: An error was detected during execution.
* try block: Code that may raise an exception is written inside this block.
* except block: Code that runs if an exception occurs in the try block.
* else block: Code that runs if no exception occurs in the try block.
* finally block: Code that runs regardless of whether an exception occurs or not, often used for cleanup actions.

### Exception Hierarchy

* Custom Exception
* Python also supports defining custom exceptions for more specific error handling.
* Used for application-based errors.

### Iterators

* Iteration: Anytime you use a loop, explicit or implicitly to go over a group of items is called iteration.
* eg. n = [1,2,3,4]
* for a in n:
  print(a)
* Iterator: It is an object that allows a programmer to traverse a sequence of data without storing the entire data in memory.
* Iterator stores only 1 item at a time in memory. Performs operation & removes from memory.
* Every iterator is also an iterable.
* Every iterator has both iter function as well as next function.
* Iterable: It is an object on which one can iterate over.
* eg. L = [1,2,3,4]
* type(L)
* type(iter(L))
* Not all iterable are iterators.
* Every iterable has an iter function.

### Generators

* It is a simple way of creating iterators.
* It doesn't have a return statement instead it has a yield keyword that returns the generator object.
* Yield is used in Python generators.
* A generator function is defined just like a normal function, but whenever it needs to generate a value, it does so with the yield keyword rather than return.
* When to Use Yield Instead of Return
  * Use yield when you want to iterate over a sequence, but don't want to store the entire sequence in memory.
  * Use yield when you want to produce a sequence of values over time, rather than computing them at once and sending them back like a list.

## Thank you for reading!

I'd love to hear your thoughts or questions about this blog on the Python file and exception handling. Feel free to join the conversation in the comments below!
Let's continue the discussion on other platforms too. Connect with me on LinkedIn or Github for more data science insights and discussions. If you found this blog helpful, consider sharing it with your network!

### Connect with me:

* Github: shrutibharat01
* LinkedIn: shrutibhrarat0105

