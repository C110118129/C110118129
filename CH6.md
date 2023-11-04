## 請新增一個CShape的子類別CTriangle，其constructor 共有三個double的參數 a,b,c (為直角三角形的三個邊長)，其面積為0.5*a*b，請寫出CTriangle的類別程式與產生其物件的main 程式(顏色為紅色，a=3, b=4, c=5) 

```CShape.java
abstract class CShape{
  protected String color;
  public void setColor(String str){
    color=str;}
  public avstract void show();}
```
```CTrinagle.java
class CTrinagle extends CShape{
  double ca,cb,cc;
  public CTriangle(double a,double b,double c)[
    Ca=a;
    Cb=b;
    Cc=c}
  public void show(){
    System.out.print("color="+color+" ");
    System.out.print("area="+0.5*Ca*Cb);}
}
```
## 一個學生可以上0到10門課
```java
import java.util.ArrayList;
import java.util.List;

public class Student {
    private String name;
    private List<Course> courses;

    public Student(String name) {
        this.name = name;
        this.courses = new ArrayList<>();
    }

    public boolean addCourse(Course course) {
        if (courses.size() < 10) {
            courses.add(course);
            return true;
        }
        return false;
    }

    public boolean removeCourse(Course course) {
        return courses.remove(course);
    }

    public List<Course> getCourses() {
        return courses;
    }

    // Other getters, setters, and relevant methods
}

public class Course {
    private String courseName;

    public Course(String courseName) {
        this.courseName = courseName;
    }

    // Getters, setters, and other relevant methods
}
```
  
