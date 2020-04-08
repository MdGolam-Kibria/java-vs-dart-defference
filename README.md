# java-vs-dart-defference

Dart
   *Dart doesn't support overloading.
   *Dart doesn't allows two costrucor make together.
   *Dart doesn't support arrays.this is possibe by collections like list,set,map etc.
   %%% if i don't have any default constructor then how to make this default class obect like  below fig 1.1
   or how to get an veriable or method using the class obect
   
#solution_Custom_Constructor


void main(){
var obj = B.anayname();//This is custom constructor calling way.
print(obj.name);//output = anika akter akhi
}
class B{

String name ="anika akter akhi";
//custom constructor syntex
B.anayname();//This is custom contructor syntax in Dart
}
   #fig 1.1 below    
   
   void main(){
   new A()//but here show error because Dart dont  allows two costrucor make together.
   }
   class A{
   
   
   int b = 12;
   A(){//but here show error because Dart dont  allows two costrucor make together.
    default constructor
   }
   A(int a){
   print("&{a}   This is parameterized constructor");
    }
   }
   
Java
   * java support overloading.
   * java allows two costrucor make together.
   *Java support arrays.
