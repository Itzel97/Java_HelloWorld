# Java Hello World


To create Classes in Java it need to start with a capital letter like "HelloWorld" if the name has more than one word each one of them will have a capital letter at the beginning.
The extention of the file is .java  

To send data to the console :
```
public class HolaMundo {
    
    public static void main (String args[]){
        System.out.println("Hello Word");
    }
                             
}
```

### Main()

The main() method is a special method in Java Programming that serves as the externally exposed entrance point by which a Java program can be run. To compile a Java program, you doesn't really need a main() method in your program. But, while execution JVM ( Java Virtual Machine ) searches for the main() method and starts executing from it.

The main() method must be public, it means that you can call this method from outside of the class you are currently in. Since it's static method , there doesn't need to be an instantiation of the class. It must not return any value, and it must accept a String array as a parameter.

### String args[]
These are the arguments of type String that your Java application accepts when you run it. Java main() method accepts only string type of argument and stores it in a string array. It is a collection of Strings , separated by a space, which can be typed into the program on the terminal.

As the Java language allows the brackets [] to be positioned after the type or the variable (the first is generally preferred)

### System.out.println()

Is a statement which prints the argument passed to it. The println() method display results on the monitor. Usually, a method is invoked by objectname.methodname().

### Capital sensitive.
Java is capital sensitive, so if we create a variable like "One" an another "one", they are two different variables.
