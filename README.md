# java-syntax_
In the previous chapter, we created a Java file called Main.java, and we used the following code to print "Hello World" to the screen:


Main.java

public class Main {
  public static void main(String[] args) {
    System.out.println("Hello World");
  }
}

#Example explained

Every line of code that runs in Java must be inside a class. In our example, we named the class Main. A class should always start with an uppercase first letter.

Note: Java is case-sensitive: "MyClass" and "myclass" has different meaning.

The name of the java file must match the class name. When saving the file, save it using the class name and add ".java" to the end of the filename. To run the example above on your computer, make sure that Java is properly installed: Go to the Get Started Chapter for how to install Java. The output should be:

Hello World

The main Method
The main() method is required and you will see it in every Java program:

public static void main(String[] args)

Any code inside the main() method will be executed. Don't worry about the keywords before and after main. You will get to know them bit by bit while reading this tutorial.

For now, just remember that every Java program has a class name which must match the filename, and that every program must contain the main() method.
