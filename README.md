# EX08-Inheritance

## Aim:

To write a C# program to print some messages using hierarchical inheritance.

## Algorithm:

step 1: Create a base class.

Step 2: Create two child class.

step 3: Create a constructor in the base class and print a message.

step 4: create a function in child class to print a message.

## Program:
```
Name : KAVIYA SHREE S

Reg.no: 212222110018

using System;
namespace inheritance
{
    public class tyre
    {
        public virtual void display()
        {
            Console.Write("Tyre is attached to: ");
        }
    }

    public class car : tyre
    {
        public override void display()
        {
            base.display();
            Console.WriteLine("Car");
        }
    }

    public class scooter : tyre
    {
        public override void display()
        {
            base.display();
            Console.WriteLine("Scooter");
        }
    }
    public class main
    {
        public static void Main(string[] args)
        {
            car c = new car();
            c.display();
            Console.WriteLine();
            scooter s = new scooter();
            s.display();
        }
    }
}

```

## Output:
<img width="863" alt="image" src="https://github.com/kaviya2839/Inheritance/assets/120553351/3fd99ced-704f-4fec-99de-9fb503abcbb3">

## Result:
Thus C# program to print some messages using hierarchical inheritance is written and executed sucessfully.
