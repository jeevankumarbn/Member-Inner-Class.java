class outerClass {
    private int x;
    
   class innerClass {
      int x = 10;
       void display()
       {
           System.out.println("X = " + x);
       }
   }
}
       
class Main {
public static void main(String[] args){
    
    outerClass o = new outerClass();
    outerClass.innerClass obj = o.new innerClass();
    obj.display();
}
}
         
         
