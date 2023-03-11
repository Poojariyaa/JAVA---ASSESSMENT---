# JAVA---ASSESSMENT---
# Pooja V
# 212221040122
## 1.Write a Java program to print the sum, multiply, subtract, divide and remainder of two numbers.

~~~java
 import java.util.Scanner;
 public class Main {
     public static void main(String[] args)
     {

        Scanner s=new Scanner(System.in);
        int a=s.nextInt();
        int b=s.nextInt();
        System.out.println("Sum of the input number:"+(a+b));
        System.out.println("Difference of the input number:"+(a-b));
        System.out.println("Product of the input number:"+(a*b));
        System.out.println("Quotient of the input number:"+(a/b));
        System.out.println("Remainder of the input number:"+(a%b));
     }
 }
~~~
## OUTPUT
![WhatsApp Image 2023-03-11 at 7 33 19 PM](https://user-images.githubusercontent.com/127511817/224497100-8b6b7827-0122-4c05-9b70-db65826ad590.jpeg)



## 2.Write a Java program to compare two numbers.

~~~java
import java.util.Scanner;
public class Main {
    public static void main(String[] args)
    {
        Scanner s=new Scanner(System.in);
        int x=s.nextInt();
        int y=s.nextInt();
        if(x>y)
        {
            System.out.println(x+" is greater than "+y);
        }
        else if(x<y)
        {
            System.out.println(y+" is greater than "+x);
        }
        else
        {
            System.out.println("Both inputs are equal");
        }
    }
}
~~~
## OUTPUT
![WhatsApp Image 2023-03-11 at 7 36 08 PM](https://user-images.githubusercontent.com/127511817/224497079-4c00f068-9838-4eda-a41e-590babcbfae0.jpeg)



 ## 3.Write a Java program to convert a string to an integer.

~~~java
public class Main {
    public static void main(String[] args)
    {
        String sc="200";
        int i=Integer.parseInt(sc);
        System.out.println(i);
        
    }
}
~~~
## OUTPUT
![WhatsApp Image 2023-03-11 at 7 37 35 PM](https://user-images.githubusercontent.com/127511817/224497039-62ae1024-f527-46e7-b223-bb49fc9dea36.jpeg)



## 4.Java Program to find area of rhombus

~~~java
import java.util.Scanner;
public class Main {
    public static int rhombus(int p,int q)
    {
        return ((p*q)/2);
    }
    public static void main(String[] args)
    {
        Scanner s=new Scanner(System.in);
        int d1=s.nextInt();
        int d2=s.nextInt();
        System.out.println(rhombus(d1,d2));
        
    }
}
~~~
## OUTPUT
![WhatsApp Image 2023-03-11 at 7 39 02 PM](https://user-images.githubusercontent.com/127511817/224496974-95a3309e-8873-4452-abeb-848c59fd414c.jpeg)



## 5.Write a Java program to find the number of days in a month

~~~java
import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        Scanner in = new Scanner(System.in);
        String str = in.nextLine();
        switch(str)
        {
            case "January":
                System.out.println("31");
                break;
            case "February":
                System.out.println("28");
                break;
            case "March":
                System.out.println("31");
                break;
            case "April":
                System.out.println("30");
                break;
            case "May":
                System.out.println("31");
                break;
            case "June":
                System.out.println("30");
                break;
            case "July":
                System.out.println("31");
                break;
            case "August":
                System.out.println("31");
                break;
            case "September":
                System.out.println("30");
                break;
            case "October":
                System.out.println("31");
                break;
            case "November":
                System.out.println("30");
                break;
            case "December":
                System.out.println("31");
                break;
        }
    }
}
~~~
## OUTPUT
![WhatsApp Image 2023-03-11 at 7 53 46 PM](https://user-images.githubusercontent.com/127511817/224497545-74922299-0f36-4318-8cd7-f2723bd968d9.jpeg)



## 6.Write a Java program to print the even numbers from 1 to 20.

~~~java
public class Main {
    public static void main(String[] args)
    {
        int i;
        for(i=1;i<=20;i++)
        {
            if(i%2==0)
            {
                System.out.println(i);
            }
        }
        
    }
}
~~~
## OUTPUT
![WhatsApp Image 2023-03-11 at 8 09 45 PM](https://user-images.githubusercontent.com/127511817/224496798-7c49f70b-ccfe-442f-9fcc-161986bf6158.jpeg)


## 7.Write a Java program to create a simple calculator.

~~~java
import java.util.Scanner;
public class Main {
    public static void main(String[] args)
    {
        Scanner s=new Scanner(System.in);
        int re=s.nextInt();
        int se=s.nextInt();
        String sym=s.next();
        switch (sym)
        {
            case "+":
                System.out.println(re+se);
                break;
            case "-":
                System.out.println(re-se);
                break;
            case "*":
                System.out.println(re*se);
                break;
            case "/":
                System.out.println(re/se);
                break;
            case "%":
                System.out.println(re%se);
                break;
            case "&":
                System.out.println(re&se);
                break;
            case "|":
                System.out.println(re|se);
                break;

        }
        
    }
}
~~~

## OUTPUT
![WhatsApp Image 2023-03-11 at 7 56 22 PM](https://user-images.githubusercontent.com/127511817/224497151-f630ff06-f0a1-4330-8990-834a17d4d7fa.jpeg)


## 8.Write a Java program to print multiplication table of given number

~~~java
import java.util.Scanner;
public class Main{
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        int x = sc.nextInt();
        for(int i=1;i<=10;i++)
        {
            System.out.println(x+" * "+i+" = "+(x*i));
        }
    }
}
~~~
## OUTPUT
![WhatsApp Image 2023-03-11 at 8 26 45 PM](https://user-images.githubusercontent.com/127511817/224497183-b8c80f79-dd13-4670-af56-1d014b9cd0fb.jpeg)
