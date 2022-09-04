# Largest-of-three-numbers
## Aim:
To write a C# program to find the largest of three numbers

## Algorithm:
### Step1: 
Start
### Step2:
Create a class and declare three variable with integer datatype
### Step3:
Use if condition to check whether num1 is largest than num2 and num3
### Step4:
Use elif condition to check whether num2 is largest than num1 and num3
### Step5:
Use else condition to display that third variable is largest among all the variables
### Step6:
stop

## Program:
```c#
using System;
namespace largestnum
{
    class Program
    {
        static void Main(string[] args)
        {
            int num1, num2, num3;
            
            num1 = Convert.ToInt32(Console.ReadLine());
            num2 = Convert.ToInt32(Console.ReadLine());
            num3 = Convert.ToInt32(Console.ReadLine());
            
            if(num1 > num2 && num1 > num3)
            {
                Console.WriteLine("The Largest Number is " + (num1));
                
            }
            
            else if(num2 > num1 && num2 > num3)
            {
                Console.WriteLine("The Largest Number is " + (num2));
                
            }
            else
            {
                Console.WriteLine("The Largest Number is " +(num3));
                
            }
            
        }
        
    }
    
}
```

## Output:
![Screenshot 2022-08-30 090422](https://user-images.githubusercontent.com/70213227/187455733-7dff1cb7-71c7-4c28-90f6-c2465041d425.png)

## Result:
Thus the C# program to find the largest of three numbers is executed successfully
