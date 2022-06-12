# Inheritance

## Aim:
To write a C# program to print some messages using hierarchical inheritance.

## Algorithm:

step 1:
Create a base class.

step 2:
Create two child class.

step 3:
Create a constructor in the base class and print a message.

step 4:
create a function in child class to print a message.

## Program:

```python
using System;
namespace fawzi
{
    public class vehicle
    {
        public vehicle()
        {
            Console.Write("tyre is attached");
        }

    }
    public class car : vehicle
    {
        public void display()
        {
            Console.Write(" to car");
        }
    }
    public class scooter : vehicle
    {
        public void display()
        {
            Console.Write(" to scooter");
        }
    }
    public class program
    {
        public static void Main(string[] args)
        {
            car car = new car();
            car.display();
            Console.WriteLine();
            scooter scooter = new scooter();
            scooter.display();
            Console.ReadKey();
        }
    }
}
```python

## Output:

![output2](https://user-images.githubusercontent.com/75235022/173239309-5ab06789-d8c5-4ca6-aa53-9309edcf6a34.png)


## Result

C# program to print some messages using hierarchical inheritance is implemented successfully.
