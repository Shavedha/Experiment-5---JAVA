# Experiment-5---JAVA
## AIM 
To create a Java program to print the below table.
```
Write a program that would print the information (name, year of joining, salary, address) of 
three employees by creating a class named 'Employee'. The output should be as follows:
Name           Year of joining                Address
 Robert              1994                  64C- WallsStreat
 Sam                 2000                  68D- WallsStreat
 John                1999                  26B- WallsStreat
 
```
## ALGORITHM 
1. Define a class named 'Employee' with the following attributes: 'name', 'year_of_joining', 'salary', and 'address'.
2. Inside the class, initialise the attributes with the provided values.
3. Create three instances of the 'Employee' class, each representing an employee with their respective information.
4. Store these instances in variables, providing the necessary values for each attribute.
5. Print the header line with the column names: 'Name', 'Year of joining', and 'Address'.
6. Print the information of each employee by accessing the attributes.
6. Run the program and observe the output displaying the information of the three employees in a tabular format.
## PROGRAM
```
import java.util.Scanner;
class Employee
{
    String Name;
    int Year;
    String Address;
    Employee(String nam,int years, String addr)
    {
        Name=nam;
        Year=years;
        Address=addr;}
    void Sam()
    {
        System.out.println(Name+ " " +Year + " " +Address); }
    void Robert()
    {
        System.out.println(Name+ " " +Year + " " +Address);}
    void John()
    {
        System.out.println(Name+ " "+Year + " " +Address);
    }
}
class Main
{
    public static void main(String args[])
    {
        System.out.println("Name    " + "Year of Joining   " + "    Address" );
        Employee e=new Employee("Sam         ", 2000, "        68D-WallsStreet");
        e.Sam();
        Employee e1=new Employee("Robert      ", 1994, "        64C-WallsStreet");
        e1.Robert();
        Employee e2=new Employee("John        ", 2002, "        70F-WallsStreet");
        e2.Sam();
    }
}
```
## OUTPUT
<img width="348" alt="image" src="https://github.com/Shavedha/Experiment-5---JAVA/assets/93427376/8d75e0a8-0746-46ff-8d0c-f239d95dae17">

## RESULT
Thus the desired output is created using Java programming. 
