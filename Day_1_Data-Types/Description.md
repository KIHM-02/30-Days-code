# Data types

Java has 8 primitive data types: byte, short, int, long, float, double, boolean, and char. For most challenges, you'll only need to concern yourselves with int and doubles. Another important data type we mentioned yesterday is the String class, whose objects are immutable strings of characters.

## Addive Operator

The operator + is used to do addition and concatenation. If you are working with numbers and use the + operator, you are doing an addition, but when you use it on strings, you will be concatenating both. 

For example:

`int a = 2, b = 3, addition = 0;`
`string s1 = "Hello ", s2 = "World" ;`

`addition = a + b;`
`System.out.println(s1 + s2);`

The output will be:
`5`
`Hello World`

## C++

In C++, it is normal to consume/skip the cin.getline after some cin>>
to avoid it, you will use:

`cin.ignore();`

Or

`getline(cin >> ws, var_name);`

The latter is more used when we have a string of type string instead of char[n];

To concatenate in c++ you must use:

`cout<<message_one<<" "<<message_two<<endl;`