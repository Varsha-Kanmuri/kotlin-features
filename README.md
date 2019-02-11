# kotlin-features
Working on some cool features of Kotlin and how it compares with Java .

1) Printing in Kotlin 

      - Reduces a lot of boiler plate code
      - Internally calling System.out.println()
      
                                   Java                                  Kotlin
                      System.out.println("Hello World");      |    println("Hello, World!")
                                                              

2) Declaring variables and constants 

     - Variables are declared using 'val' or 'var' , provided they are immutable or mutable.
     - Java uses additional 'final' keyword to make variables immutable
     - Advantages using 'val' : Concise , predictable behavior, thread safety
                     
                     
                       int number = 10 ;                       |     var number = 10
                       final int radius = 5;                   |     val radius = 5;
                       
                       
3) Strings in Kotlin  

     - Like Java, strings are immutable in Kotlin
     - Use val keyword to declare strings

                       String name = "JAVA" ;                  |     val greeting = "KOTLIN"
                    
                       
4) String literals

    - Escaped string vs Raw Strings
    - Escaped string can contain escape characters in them
         val escString = "Kotlin escaped string!\n"
    - Raw string can contain newlines and arbitrary text, is delimited by a triple quote """ .
           val myString = """
                   line 1 
                   line 2
           """

5) String concatenation
   
    String firstName = "Varsha";                                 |   val firstName = "Varsha"; 
    String lastName = "Kanmuri";                                 |   val lastName = "Kanmuri";
    print("My name is: " + firstName + " " + lastName);          |   val message = "My name is: $firstName $lastName"
    

    
