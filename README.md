# Java1
// Online Java Compiler
// Use this editor to write, compile and run your Java code online
import java.util.*;
class  FirstProgram{
    String name;
    void sound(String sound){
        System.out.println(sound);
    }
    public static void main(String[] args) {
        FirstProgram p1=new FirstProgram();
        p1.name="Black";
         System.out.println(p1.name);
        p1.sound("jbl");
        FirstProgram p2=new FirstProgram();
        p2.name="Red";
         System.out.println(p2.name);
        p2.sound("Sony");
    }
}
Constructors
import java.util.*;
class FirstProgram{
     int mil;
     {
         mil=90;
     }
     FirstProgram(int m){
         mil=m;
     }
    FirstProgram(FirstProgram ob1){
         this.mil=ob1.mil;
     }
    
    public static void main(String[] args) {
        FirstProgram obj=new FirstProgram();
        System.out.println(obj.mil);
        
        FirstProgram ob1=new FirstProgram(20);
        System.out.println(ob1.mil);
        FirstProgram ob2=new FirstProgram(obj);
        System.out.println(ob2.mil);
    }
}
Inheritance
import java.util.*;
class father{
   void work(){System.out.println("Working");}
}
class son extends father{
    void play(){System.out.println("Playing");}
}
 public class FirstProgram{
    public static void main(String[] args) {
        son s=new son();
        s.play();
        s.work();
    }
}
Overloading & Overwriting
import java.util.*;
public class Overloading {
    static int add(int x,int y){
        return x+y;
    }
       static double add(double x,double y){
        return x+y;
    }
    public static void main(String[] args) {
        System.out.println(add(2,3));
        System.out.println(add(13.9,3.5));
        
    }
}
