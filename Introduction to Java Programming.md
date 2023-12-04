Welcome too Java class. In this class you will be learning the basics of Java Programming language and will be able to create your first console apps that runs on Windows, MacOS and Linux operating systems.

**What is Java**
Java is a high-level, general-purpose programming language that is designed to be platform-independent, meaning that Java programs can run on any device or operating system with a Java Virtual Machine (JVM). It was developed by Sun Microsystems (now owned by Oracle) and released in 1995. Key features of Java include its simplicity, object-oriented nature, and the use of a virtual machine to execute code, which enhances portability. Java is widely used for building a variety of applications, including web applications, mobile apps (Android is primarily built using Java), enterprise systems, and more. It supports multithreading, has a rich set of libraries and APIs, and is known for its strong security features. The language is particularly popular for its "write once, run anywhere" philosophy, which enables developers to create applications that can run on different platforms without modification.

**What Is A Variable?**
Variables in programming languages are containers for storing and manipulating data. They have a name, a data type that defines the kind of values they can hold (such as numbers or text), and a scope that determines where in the program they can be used. Variables allow programmers to work with data dynamically and efficiently in their code.

*For Example*

> **int** number1 = 0;
> in the example above **number1** is the *variable that stores the value of 0 inside* and **int** is the **type** of the variable. 
> *int* only stores the *whole numbers* values inside.

>**String** name = "YOUR_NAME";
>in the example above **name** is the *variable that stores the value of YOUR_NAME inside* and **String** is the **type** of the variable.
>*String* only stores *text* values inside.

>**double** number2 = 88.88;
>in the example above **number2** is the *variable that stores the value of 88.88 inside* and **double** is the **type** of the variable.
>*double* only stores *decimal number* values inside.

**Practice**
Now, since we now know what the variables and the variable types are we can go ahead and create our first app using *Java Programming language*.

> *package* class10_18;
> 
> *public class* FirstClass{
> 	*public static void* main (*String[] args*){
> 	
> 		*String* fullName = "Ata Yigit Uzay Ustundag";
> 		*int* age = 22;
> 		*double* height = 185.8;
> 		
> 		*System*.*out*.*println*(*"Name:"* + fullName + *"\nAge: "* + age.ToString() + *"\nHeight: "* + height.ToString());
> 		
> 	}
> } 
> in the example above, 
> 	The *System*.*out*.*println*(); is a method that we use to display the variables or the values on the console/terminal.
> 	
> 	.*ToString*() is the method we use to convert *non-String* values to *String* values.
> 	
> 	*\n* is a escape method to use when you want to display values in the next line.



