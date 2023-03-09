# Exceptions and errors handling
The Java language has a special mechanism for handling errors that may occur at program execution time. Unlike other languages, the appearance of an error causes the immediate interruption of the program, but in Java we can handle this error situation in an adequate way and thus avoiding the interruption of the program.

An exception is basically a Java class represented in its most generic form by the class java.lang.Exception, so all exceptions that occur during the execution of your program can be treated as objects of type Exception.

An important feature about exceptions is that, because they can occur at any time, they are literally “thrown” back into the execution chain and calling the classes.
