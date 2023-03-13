# Eligibility-for-Admission

## Aim:
To write C# program to find the eligibility for admission to an engineering course

## Algorithnm:

## Program:
```
using System;
public class Exercise10
{
    public static void Main()
    {
        int p, c, m;

        


        Console.Write("Input the marks obtained in maths :");
        p = Convert.ToInt32(Console.ReadLine());
        Console.Write("Input the marks obtained in physics :");
        c = Convert.ToInt32(Console.ReadLine());
        Console.Write("Input the marks obtained in chemistry :");
        m = Convert.ToInt32(Console.ReadLine());
        Console.Write("Total marks of Maths, Physics and Chemistry : {0}\n", m + p + c);
        Console.Write("Total marks of Maths and  Physics : {0}\n", m + p);

        if (m >= 65)
            if (p >= 55)
                if (c >= 50)
                    if ((m + p + c) >= 180 || (m + p) >= 140)
                        Console.Write("The  candidate is eligible for admission.\n");
                    else
                        Console.Write("The candidate is not eligible.\n\n");
                else
                    Console.Write("The candidate is not eligible.\n\n");
            else
                Console.Write("The candidate is not eligible.\n\n");
        else
            Console.Write("The candidate is not eligible.\n\n");
    }
}


```




## Output:




## Result:
