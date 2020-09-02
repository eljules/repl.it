# Using repl.it for your CS235 Lab Projects
Although you can use whatever development environment you want for CS 235 labs, the repl.it service only requires you to have a computer with a web browser, so you can develop your code without installing compilers and other development options.
## Getting Started
First go [repl.it](https://repl.it/) and sign up for an account.
![Sign Up](https://github.com/BYUCS235/BYUCS235.github.io/blob/master/replItCreateAccount.png)

## Signing In
You will now need to read your email and look for a verification message.  Verify your account and you should be able to log in and see the welcome screen.
![Verify](https://github.com/BYUCS235/BYUCS235.github.io/blob/master/replitVerification.png)
Answer the questions to configure your account
## Create a new repl
Create a new repl and call it Test
![NewRepl](https://github.com/BYUCS235/BYUCS235.github.io/blob/master/replitNewRepl.png)
Select the C++ option since that is what you will be using in class.
![NewRepl2](https://github.com/BYUCS235/BYUCS235.github.io/blob/master/replitNewRepl2.png)
## Development Console
You should now see the development console with the file viewer on the left and your command prompt on the right
![NewRepl2](https://github.com/BYUCS235/BYUCS235.github.io/blob/master/replitViewHello.png)
Notice that there is a hello.cpp file included with your default account.  
## Building an application
1) Create a new folder with the +folder in the upper left.  Call it Lab1
2) Create a new file in that folder with the +file in the upper left. Call it main.cpp
3) Copy the hello world program and put it into the main.cpp window
```
#include <iostream>

int main() {
  std::cout << "Hello World!\n";
}
```
3) In the command line black window on the right, change directory into the Lab1 folder "cd Lab1"
4) Compile the main.cpp file with "g++ -o main main.cpp"
5) Run the program with "./main".  You should see the "Hello World" output.
![NewRepl2](https://github.com/BYUCS235/BYUCS235.github.io/blob/master/replitMake.png)


