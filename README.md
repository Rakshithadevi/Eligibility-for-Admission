# Eligibility-for-Admission

## Aim:
To write C# program to find the eligibility for admission to an engineering course

## Algorithnm:
```
1) Start the program
2) Declare variables to store physics, chemistry and math marks, total marks and percentage.
3) Ask the user to input the physics, chemistry, and math marks.
4) Read the values of physics, chemistry, and math marks from the user.
5) Calculate the total marks as the sum of physics, chemistry, and math marks.
6) Calculate the total marks as the sum of physics and math marks.
7) Check if the total mark of maths, physics and chemistry is greater or equal to the given condition or total marks of maths and physics is greater then or      equal to given condition.
8) If the conditions in step 7 are true, display "You are eligible for admission to an engineering course."
9) If the conditions in step 7 are false, display "You are not eligible for admission to an engineering course."
10)End the program
```

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
![e1](https://user-images.githubusercontent.com/94165326/225869713-484ef170-b096-4ec9-b518-3e5d00f8494e.png)





## Result:
Thus, the C# program to find the eligibility for admission to an engineering course has been executed successfully.
