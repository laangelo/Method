public class Methods {

// Non-static method
public void nonStaticMethod() {
System.out.println("This is a non-static method.");
    }

// Static method 1
public static void staticMethod1() {
System.out.println("This is static method 1.");
    }

// Static method 2
public static void staticMethod2() {
System.out.println("This is static method 2.");
    }

// Constructor
public ExampleProgram() {
System.out.println("This is the constructor.");
    }

public static void main(String[] args) {
// Create an instance of the class
ExampleProgram example = new ExampleProgram();
 // Call the non-static method using the instance
example.nonStaticMethod();

// Call the static methods using the class name
ExampleProgram.staticMethod1();
ExampleProgram.staticMethod2();
    }
}

