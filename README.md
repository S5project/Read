//java code to add 2 num



import java.util.Scanner; // Import the Scanner class

class MyClass {
  public static void main(String[] args) {
    int x, y, sum;
    Scanner myObj = new Scanner(System.in);                   // Create a Scanner object
    System.out.println("Type a number:");
    x = myObj.nextInt();                                    // Read user input

    System.out.println("Type another number:");
    y = myObj.nextInt();                                        // Read user input

    sum = x + y;                               // Calculate the sum of x + y
    System.out.println("Sum is: " + sum);          // Print the sum
  }
} 
//using constructor
import java.util.Scanner;
class add 
{
    int a,b;
    add()
    {
        a=0;
        b=0;
    }
    add(int x,int y)
    {
        a=x;
        b=y;
    }
    void addition()
    {
        int c=a+b;
        System.out.println("Addition: "+c);
    }
    void display()
    {
        System.out.println("X "+a+"Y: "+b);
    }
    
}

class constructor
{
    public static void main(String args[])
    {
        add aa=new add();
        aa.display();
        Scanner sc=new Scanner(System.in);
        int x;
        x=sc.nextInt();
        int y;
        y=sc.nextInt();
        add bb=new add(x,y);
        bb.addition();
    }
}
