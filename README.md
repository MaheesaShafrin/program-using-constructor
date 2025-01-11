# program-using-constructor
class Student {
String name;
int rollNumber;
Student(String name, int rollNumber) {
this.name = name;
this.rollNumber = rollNumber;
}
public void display() {
System.out.println(&quot;Name: &quot; + name);
System.out.println(&quot;Roll Number: &quot; + rollNumber);
}
}
public class ConstructorExample {
public static void main(String[] args) {
Student student = new Student(&quot;John&quot;, 101);
student.display();
}
}
Output
Name: John
Roll Number: 101
