# Getter-and-setter-method-
class Student {
    private String name;
    private int age;
    public void setName(String name) {
        this.name = name;
    }
    public String getName() {
        return name;
    }
    public void setAge(int age) {
        this.age = age;
    }
    public int getAge() {
        return age;
    }
}
public class GetterSetterExample {
    public static void main(String[] args) {
        Student student = new Student();
        student.setName("John");
        student.setAge(18);
        System.out.println("Student Name: " + student.getName());
        System.out.println("Student Age: " + student.getAge());
    }
}
