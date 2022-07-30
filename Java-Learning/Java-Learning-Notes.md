1. Commands
    System.out.println("Robots are friends to humans");

    Principle 1: 
        In Java, it is customary to write each command on a new line. A semicolon 
        goes at the end of each command.
    Principle 2: 
        A program cannot consist of only commands. Java commands must be inside 
        functions, and functions must be inside classes.
    
2. Structure of a typical program
    The code of a class usually consists of a class name and a class body. The body 
    of a class is enclosed in curly braces. 
    i.e.
        public class House
        {
            CLASS BODY
        }

    The body of the class can contain variables (also called fields) and methods (functions).
    i.e. 
        public class House
        {
            VARIABLE A

            VARIABLE Z

            METHOD 1

            METHOD N
        }

    Examples:
        public class House {

            int a;
            int b;

            public static void main (String[] args)
            {
            System.out.print(1);
            }

            public static double pi ()
            {
            return 3.14;
            }

        }
    In the example above, a and b are variables, and main and pi are methods.

3. main() method
    Classes can have variables and methods, but they don't have to. There can be classes without variables and classes without methods. There can even be classes with neither methods nor variables. Although such classes would make little sense.

    A minimal program must consist of at least one class, which must have at least one method (function) that marks the program's starting point. This method must be named main.

    



