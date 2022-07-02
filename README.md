#Palindrome


# Aim:
To write a C# program to find whether the given string is a Palindrome or not.
# Algorithm:

# Program:
`````
using System;
class HelloWorld {
  static void Main() {
    string value,dupvalue,rev="";
    value=Console.ReadLine();
    dupvalue=value;
    for(int s = value.Length-1;s>=0;s--){
        rev+= value[s];
    }
    if (rev==dupvalue)
    Console.WriteLine(dupvalue+" is a palindrom");
    else
    Console.WriteLine(dupvalue+" is not a palindrom");
    }
}

````````````````

# Output:
![Screenshot (45)](https://user-images.githubusercontent.com/75235759/163821515-00fea559-e10c-48d2-8660-3f4a0d6bb445.png)

![Screenshot (46)](https://user-images.githubusercontent.com/75235759/163821547-6a211699-1e2b-4911-a568-c71a4048ad1b.png)



# Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
