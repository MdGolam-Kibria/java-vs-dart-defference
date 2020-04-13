# java-vs-dart-defference
 
| Dart Programming  | Second Header |
| ------------- | ------------- |
|  Dart doesn't support encapsulation.  | Java support encapsulation  |
|  Dart doesn't support arrays.this is </br>possibe by collections like list,set,map etc. | java support arrays  |
|  Dart doesn't allows two constructor make together | possible  |
| ------------- | ------------- |

   <h3>if i don't have any default constructor then how to make this default class obect like  below fig 1.1
   or how to get an veriable or method using the class obect </h3></br>
   
## solution_Custom_Constructor

"void main(){</br>
var obj = B.anayname();//This is custom constructor calling way.</br>
print(obj.name);//output = anika akter akhi</br>
}</br>
class B{</br>

String name ="anika akter akhi";</br>
//custom constructor syntex</br>
B.anayname();//This is custom contructor syntax in Dart</br>

} </br>

   <h6><b>fig 1.1 below</b></h6></br>
   
   void main(){</br>
   new A()//but here show error because Dart dont  allows two costrucor make together</br>
   } </br>
   class A{</br>
   
   
   int b = 12;</br>
   A(){//but here show error because Dart dont  allows two costrucor make together.</br>
    default constructor</br>
   }</br>
   A(int a){</br>
   print("&{a} This is parameterized constructor");</br>
    }</br>
   }</br>"
   

