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
