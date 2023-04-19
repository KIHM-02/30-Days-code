# Hello, World

In this review we are going to look at a basic topic, inputs and outputs.

Each programming language has its own syntax for doing this, for example:

## Java

#### Output

To print messages on screen we use:

`System.out.println("Message on screen");`

#### Input

To use console input, you need to instantiate an object called "Scanner", this object helps you get input from the user via the keyboard.

The sintaxis is:

`import java.util.Scanner;`
.
.
.
`Scanner _objectName_ = new Scanner(System.in);`

It is recommended to only have one of this object in your entire class.


## C

In c is very simple, you only need the library:

`#include <stdio.h>`

to use printf (outputs) and scanf(inputs), for example: 

`printf("Message");`
`scanf(type, &var);`

"Type" is the data type you are using. In each programming language exists char, int, float, double, etc. These are called "primitive data types".


## C++

C++ is the upgrade of C, this language is object oriented. In this case you need to use the library:

`#include <iostream>`

and

`using namespace std;`

to declare you are using standart input and output.

`cout<<"message"<<endl;`
`cin>>var;`

# Code examples

## Java

`class HelloWorld`
`{`
`    public static void main(String[] args)`
    `{`
`        System.out.println("Hello, World!");`
`    }`
`}`

## C

`#include <stdio.h>`
`#include <stdlib.h>`

`int main()`
`{`
`    printf("Hello, World");`

`   system("pause");`
`   return 0;`
`}`



## C++

`#include <iostream>`
`#include <stdlib.h>`

`using namespace std;`

`int main()`
`{`
`    cout<<"Hello, World<<endl;`

`   system("pause");`
`   return 0;`
`}`