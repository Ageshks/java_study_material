# java_study_material

1. Create a 'Person' Class: Develop a Java class named 'Person' with attributes like name,
  age, and a method to display these details. Instantiate and display the information of two
  different people.
ans)
            public class person{
          String name;
          int age;
          public person(String name, int age){
            this.name = name;
            this.age = age;
          }
          public  void display(){
            System.out.println("name: "+name);
            System.out.println("age: "+age);
          }
          public static void main(String[] args) {
            person person1 = new person("agesh", 27);
            person person2 = new person("anneesha", 24);
            person1.display();
            System.out.println("\n");
            person2.display();
          }
