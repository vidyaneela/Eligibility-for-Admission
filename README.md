# Eligibility-for-Admission

## Aim:
To write C# program to find the eligibility for admission to an engineering course

## Algorithnm:
### STEP1 : Start the program and declare the variables required.

### STEP2 : Obtain the input from the user and read the values.

### STEP3 : Calculate the total marks and check for the conditions.

### STEP4 : Print the required output.

### STEP5 : End the program.


## Program:
```
Name : M.Vidya Neela
Reg no : 212221230120
```
```
using System;
namespace Hello
{
    public class program
    {
        public static void Main()
        {
            int phy,chem,maths;
            Console.WriteLine("Enter the physics mark");
            phy = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Enter the chemistry mark");
            chem =Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Enter the maths mark");
            maths = Convert.ToInt32(Console.ReadLine());
            if (maths >= 65 && phy >= 55 && chem >= 50)
            {
                if ((maths + phy + chem) >= 180 || (maths + phy) >= 140)
                    Console.WriteLine("Student is eligible");
                else
                    Console.WriteLine("Student is not eligible");
            }
            else
                Console.WriteLine("student is not eligible");
        }
    }

}

```

## Output:

![image](https://github.com/vidyaneela/Eligibility-for-Admission/assets/94169318/e057c4bb-9774-41b6-a284-cb7b78d4954a)

## Result:
Thus,the program to find the eligibility for admission is executed successfully.
