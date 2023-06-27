# Dart Programming Tutorial for Beginners 

Learn Dart Programming, its basics and Fundamentals from scratch.

## Topics to be covered

0. Overview
    - Course introduction, prequisites and software required
1. Installation
    - Install required softwares for Windows, MAC and Linux ( Ubuntu )
2. Getting Started with Dart Programming
    - Run your first app in Dart
    - Comments
3. Exploring Data Types and Variables 
    - Data Types and Variables
    - String, Literals and String Interpolation
    - Define constants using "final" and "const" keywords
4. Control Flow Statements 
    - IF ELSE 
    - Conditional Expressions
    - Ternary Operator 
5. Loop Control Statements 
    - What are Iterators?
    - FOR Loop and how it works
    - WHILE Loop
    - DO WHILE Loop 
    - BREAK statements 
    - CONTINUE keyword 
    - Labelled FOR Loop 
6. Exploring Functions or Methods 
    - Declaring functions 
    - Function Expressions: Short hand syntax or using FAT ARROR 
    - Optional Positional Parameters 
    - Optional Named Parameters 
    - Optional Default Parameters 
7. Exception Handling
    - Demo with example
    - Custom Exception Class 
8. Object Oriented Programming: Getting Started 
    - Defining Class and creating Objects
    - Instance and field variables 
    - Constructors
      - Default
      - Named
      - Parameterized 
9. More on Object Oriented Dart 
    - Inheritance
    - Getter and Setter
    - Private Instance Variable 
    - Polymorphism 
    - Using constructors in Inheritance
    - Static variables and methods 
10. Functional Programming in Dart
    - Lambda Expression
    - Higher-Order Functions
    - Lexical Closures 
11. Dart Collections 
    - Arrays or List
        - Fixed Length List
        - Growable List
    - Set and HashSet 
    - Map and HashMap 
12. Callable Classes 
13. Conclusion 


# Hello World

```
void main(){
  
  print("Hello World");
  print("Hi_1");
  print("Hi_2");
  print("Hi_3");
  print("Hi_4");
  print(36/4);
  print(false);
  print("hello");
  print(121222*20230);
  print(200000%23);
  print(787/33);
  print("helo my name is devanshu");
  print("how are you");
  print("System");
  print("kkkk");
  print("42323232323 + 3434343434");
  print("Tutorials");
  print("We are they hello");
  print("Dear is out");
}

```
# Buid Data Type

```
void main(List<String> arguments){
  
  int score = 23;
  int count = 23;
  int hexValue = 0xEADEBAEE;
  String chu = "ggddgdgdg";
  var game = "palyer";
  var games1 = "pay";
  int ck = 233;
  double hhh = 796.788;
  double percentage = 93.4;
  var percentagea = 82.33434;
  String name = "Hello";
  var company = "Google";
  bool isValid = true;
  var isAlive = false;
  

  print(company);
  print(name);
  print(count);
  print(hexValue);
  print(chu);
  print(game);
  print("hello ${percentage}");
  print("game i play ${hhh} ${percentage} ${percentagea}");
  print(games1);
  print(ck/2);
  print(hhh-ck);
  print(isValid);
  print(isAlive);
  print(score);
  print(ck*1000000);
}

```
# String Interpolation


```
void main(){
  
  var isCool = true;
  int x = 2;
  "JohnJohn";
  4.5;
  
  String s1 = 'Single';
  String s2 = 'Double';
  String s4 = 'Delete';
  String s7 = 'Privacy';
  String s9 = 'dDddd';
  String a = 'dsdsdsd';
  
  var v = 1;
  var b = 2;
  var c = 3;
  var d = 4;
  var e = 5;
  
  String s67 = 'Hi i am devanshu.'
    'This is a plan'
    'I am not you'
    'You love me';
  
  print('My Name is $s1');
  print('Hello is a toy $s7');
  
  print("$a+$b+$c+$d+$e");
  print('Dream is You');
  print('Math Math Math Math');
  print('Energy');
  print("$a * $b * $c * $d * $e");
  
  print(s1);
  print(s2);
  print(s4);
  print(s67);
  print(s7);
  print("${s1} ${s2} ${s9} ${s7}");  
  print("dkgdfkhdfd");
  print("${s1}");
  print("${s1} ${x}");  
}
```

# if else

```
void main(){
  var salary = 15000;
  
  if(salary > 20000000){
    print("You Got Promotion");
  }else{
    print("Need To Work");
  }
  
  var marks = 50;
  
  if(marks >= 90 && marks < 100){
    print("A++ Grade");
  } else if(marks >=80 && marks < 90){
    print("A Grade");
  }
  else if(marks >=70 && marks < 80){
    print("B Grade");
  }
  else if(marks >=60 && marks <60){
    print("D Grade");
  }
 else if(marks >= 30 && marks < 60){
   print("You Have Failed");
 } 
 else {
  print("Invalid Marks. Please Try Again Later");  
 } 
}
```

# conditional expressions

```
void main(){
  int a = 2;
  int b = 3;
  
  int smallNumber = a < b ? a : b;
  print("$smallNumber is smaller");
  var name = null;
  String nameToPrint = name ?? "Guest User";
  print(nameToPrint);
  
  int aaaa = a > b ? a : b;
  print("$aaaa is Good");
  var name1 = null;
  String nameToPrints = name1 ?? "Guest";
  print(nameToPrints);
  
}
```
# Switch Case

```
void main(){
  
  String grade = 'k';
 
  switch(grade){
    case 'A' :
      print('Excellent Babu');
      break;
      
    case 'B':
      print('Very Good !');
      break;
    
    case 'C':
      print('Good Work');
      break;
      
    case 'D':
      print('Failed');
      
    case 'E':
      print('Chacha Vidayak Hai');
      
    case 'k':
      print('Babua Kasa Hai');
      
    default : 
      print('Hello Hi Devanshu');
      
  }
}
``` 

# For Loop
``` 
void main(){
  
  for(int i = 1;i<=10;i++){
    if(i%2 == 0){
      print(i);
    }
  }
  
  List planetList = ["One","Two","Three","Four"];

  for(String planet in planetList){
    print(planet);
  }
  
}

```

# While Loop 1

```
void main(){
  
  var i = 1;
  
  while(i <= 10){
    if(i%2 == 0){
      print(i);
    }
    i++;
  }  
}
```

# While Loop 2

```

void main(){
  
  var i = 1;
  while(i<=10){
    if(i%2==0){
      print(i);
    }
    i++;
  }
  
print("----------------------");
  
  
  var j =0;
  while(j<100){
    if(j%10==0){
      print(j);
    }
    j++;
  }
  
print("----------------------");

  var t = 9;
  while(t<90){
    if(t%100==0){
      print(t);
    }
    t++;
  }
  
print("----------------------");
  
  var g = 3;
  while(g>0){
    print(g);
  g--;
  }
  
  
print("----------------------");
}
```

# Do While Loop

```
void main(){
  
  int i = 1;
  
  do{
    if(i%2==0){
      print(i);
    }
    i++;
  } while(i<=10);
  
  
  print("---------------------");
  
  int j = 10;
  do{
    if(j%10==0){
      print(j);
    }
    j++;
  } while(j<=100);
  
    
  print("---------------------");
  
  int k = 12;
  do{
    if(k%100 == 0){
      print(k);
    }
    k++;
  } while(k<=1000);
  
  
print("---------------------");

  int c = 10;
  do{
    print(c);
    c--;
  }while(c==10);
}
```

# Break Keyword

```
void main(){
  OuterLoop : for(int i =1;i <= 3;i++){
    InnerLoop: for(int j =1;j<=3;j++){
      print("$i $j");
      
      if(i == 2 && j == 2){
        break OuterLoop;
      }
    }
  }
  
  print("--------------------");
  
  Out : for(int p =2;p<10;p++){
    
    In : for(int g =0;g<10;g++){
      
      print("G value is : $g and P value is $p");
      if(p==g){
        break Out;
      }
    }
  }
}
```

# Continue Keyword

```
void main() {

	// CONTINUE keyword
	// Using Labels

	myLoop: for (int i = 1; i <= 3; i++) {

		myInnerLoop: for (int j = 1; j <= 3; j++) {

			if (i == 2 && j == 2) {
				continue myLoop;
			}
			print("$i  $j");
		}
	}
}
```

# Function Demo

```
void main(){
  findPerimeter(4,2);

  int rectArea = getArea(10,4);

  print("I am Rectangle");
  hello(6);
}

void findPerimeter(int length,int breadth){
  
  int perimeter = 2*(length+breadth);
  print("The Area is $perimeter");

  print("--------------------");
}


int getArea(int length,int breadth){
 int area = length * breadth;
  return area;
}

void hello(int times){
  for(int v =0;v<=times;v++){
    print("Hello Times $times");
  }  
  print("--------------------");
}
```

# Function Expression

```
void main(){
  
  findPerimeter(4,2);
  line("------------");
  hello(5);
  line("------------");
  color("blue");
  line("------------");
}

void findPerimeter(int length,int breadth) => print("The perimeter is ${2 * (length + breadth)}");

int getArea(int length, int breadth) => length*breadth;

void hello(int times) => print("hello");

void color(String colorType) => print("$colorType"); 

void line(String line) => print("$line");
```

# Optional Positional Params

```
void main(){
  
  printme1("One","two","three");
  print("");
  printme2("Six");
}

void printme1(String v1,String v2,String v3){
  print("Hi1 $v1 $v2 $v3");
}

void printme2(String t1,[String t2,String t3]){
  print("Hi1 $t1");
  print("Hi2 $t2");
  print("Hi3 $t3");
}
```

# Named Paremeter

```
// Optional Named Parameters

void main() {
	findVolume(10, breadth: 5, height: 20);
	print("");

	findVolume(10, height: 20, breadth: 5);     // Sequence doesn't matter in Named Parameter
}


int findVolume(int length, {int breadth, int height}) {

	print("Length is $length");
	print("Breadth is $breadth");
	print("Height is $height");

	print("Volume is ${length * breadth * height}");
}
```

# Default Parameter

```
void main() {

	findVolume(10);     // Default value comes into action
	print("");

	findVolume(10, breadth: 5, height: 30);     // Overrides the old value with new one
	print("");

	findVolume(10, height: 30, breadth: 5);     // Making use of Named Parameters with Default values
}


int findVolume(int length, {int breadth = 2, int height = 20}) {

	print("Lenght is $length");
	print("Breadth is $breadth");
	print("Height is $height");

	print("Volume is ${length * breadth * height}");
}
```

# Exception Handelling

```
void main(){
  
  print("CASE 1");
  
  try{
		int result = 12 ~/ 0;
    print("The Result is $result");
  } on IntegerDivisionByZeroException {
    print("Cannot divide by Zero");
  }
  print("");
  print("CASE 2");
  
  try{
    int result = 12 ~/ 0;
    print("The Result is $result");        
  }
  catch(e,s){
     print("The Exception Thrown $e");   
     print("Stack Track \n $s");
  }
  
  print("");
  print("CASE 4");
  
  try{
    int result  = 12 ~/ 3;
    print("The Result is $result");
  } catch(e){
    print("The Exception Thrown is $e");
  }
  finally{
    print("This is finnaly clause is always executed");
  }
  
  print("");
  print("Case 5");
  
  try{
    depositMoney(-200);
  }catch(e){
    print(e);    
  }
  finally{
    
  }
  
}

class DepositException implements Exception{
  String errorMessage(){
    return "You Cannot Enter Amount Less Than 0";
  }
  
}

void depositMoney(int amount){
  if(amount < 0){
    throw new DepositException();
  }
  
}
```

# Class and Oject

```
void main(){
  
  var student1 = Student();
  student1.id = 23;
  student1.name = "Devanshu";
  print("${student1.id} and ${student1.name}");
  
  student1.study();
  student1.space();
  student1.sleep();
  student1.space();
  
  var student2 = Student();
  student2.id = 32;
  student2.name = "Harsh";
  print("${student2.id} and ${student2.name}");
  
  student2.study();
  student2.space();
  student2.sleep();
  student2.space();
}


class Student{
   int id = -1;
   String name = "";
   
   void study(){
		print("${this.name} is now studying");
   }
  
  void sleep(){
    print("${this.name} is now sleeping");
  }
  
  void space(){
    print("----------------------------------------------------");
  }
  
}
```

# Constructor

```
void main() {

	var student1 = Student(23, "Peter"); 		// One Object, student1 is reference variable
	print("${student1.id} and ${student1.name}");

	student1.study();
	student1.sleep();

	var student2 = Student(45, "Sam");		// One Object, student2 is reference variable
	print("${student2.id} and ${student2.name}");

	student2.study();
	student2.sleep();


	var student3 = Student.myCustomConstructor();   // One object, student3 is a reference variable
	student3.id = 54;
	student3.name = "Rahul";
	print("${student3.id} and ${student3.name}");


	var student4 = Student.myAnotherNamedConstructor(87, "Paul");
	print("${student4.id} and ${student4.name}");
}

// Define states (properties) and behavior of a Student

class Student {
	int id = -1;
	String name;

	Student(this.id, this.name);    // Parameterised Constructor

	Student.myCustomConstructor() {                 // Named Constructor
		print("This is my custom constructor");
	}

	Student.myAnotherNamedConstructor(this.id, this.name);  // Named Constructor

	void study() {
		print("${this.name} is now studying");
	}

	void sleep() {
		print("${this.name} is now sleeping");
	}
}

```

# Getter and Setter


```
void main(){
  
  var student = Student();
  student.name = "Devanshu";
  print(student.name);
  
  student.percentage = 439.0;
  print(student.percentage);
}

class Student{
  String name = "";
  double _percent = 0.1;
  
  void set percentage(double marksSecured) => _percent = (marksSecured/500) * 100;

  double get percentage => _percent;
}

```

# Getter and Setter

```
void main(){
  var dog = Dog();
  dog.breed = "Labra";
  dog.color = "Black";
  dog.bark();
  dog.line();
  dog.eat();
  dog.line();
}

class Animal{
  String color = "";
  
  void eat(){
    print("Eat !");
  }
  
  void line(){
    print("-----------------------------");
  }
}

class Dog extends Animal {
  String breed = "";
  
  void bark(){
    print("Bark");
  }
}

class Cat extends Animal {
  int age = 0;
  void meow(){
    print("Meow.........");
  }
}
```

# Method Overriding

```
void main(){
  var dog = Dog();
  dog.eat();
  print(dog.color);
 
}

class Animal{
  String color = "brown";
  void eat(){
    print("Animal is Eating....");
  }
}

class Dog extends Animal {
  String breed = "";
  String color = "Black";
  
  void bark(){
    print("Blank");
  }
  
  void eat(){
    print("Dog Eating");
    super.eat();
    print("More Food To Eat");
  }
  
}
```
# Inheritance with Constructor

```
void main(){
  var dog1 = Dog("Lab","Blac");
  print("");
  
  var dog2 = Dog("Pug","Brown");
  print("");
  
  var dog3 = Dog.myNamedConstructor("Get","Set");
}

class Animal{
  String color = "";
  
  Animal(String color){
    this.color = color;
    print("Animal Class Constructor");
  }
  
  Animal.myAnimalNamedConstrctor(String color){
    print("Animal Class Named Constructor");
  }
  
}

class Dog extends Animal{
  
  String breed = "";
  
  Dog(String breed,String color) : super(color){
    this.breed = breed;
    print("Dog class Named Constructor");
  }
  
  Dog.myNamedConstructor(String breed,String color) : super.myAnimalNamedConstrctor(color){
		this.breed = breed;
    print("Dog class Named Constructor");
  }
}
```
# Abstract Class

```
void main(){
  
  var rectangle = Rectangle();
  rectangle.draw();
  
  var circle = Circle();
  circle.draw();
}

abstract class Shape{
  int x = 0;
  int y = 0;
  
  void draw();
  
  void myNormalFunction(){
    
  }
}

class Rectangle extends Shape{
  void draw(){
    print("Drawing Rectangle.........");
  }
}

class Circle extends Shape{
  void draw(){
    print("Drawing Circle............");
  }
}
```
# Interface

```
void main() {

	var tv = Television();
	tv.volumeUp();
	tv.volumeDown();
}

class Remote {

	void volumeUp() {
		print("______Volume Up from Remote_______");
	}

	void volumeDown() {
		print("______Volume Down from Remote_______");
	}
}

class AnotherClass {

	void justAnotherMethod(){
		// Code
	}

}

// Here Remote and AnotherClass acts as Interface
class Television implements Remote, AnotherClass {

	void volumeUp() {
//		super.volumeUp();       // Not allowed to call super while implementing a class as Interface
		print("______Volume Up in Television_______");
	}

	void volumeDown() {
		print("______Volume Down in Television_______");
	}

	void justAnotherMethod() {
		print("Some code");
	}
}
```

# Static Method

```
void main(){
  
  var circle1 = Circle();
  var circle2 = Circle();
  
  
  Circle.pi;
  Circle.pi;
  
  Circle.calculateArea();
  
  Circle.linecode();
  
  circle1.myNormalFunction();
  
  Circle.linecode();
  
  circle2.myNormalFunction();
  
  Circle.linecode();
}

class Circle {
  
  static const double pi = 3.14;
  static int maxRadius = 5;
  
  String color = "";
  
  static void calculateArea(){
    print("Some Code To Calculate Area of Circle");
  }

  void myNormalFunction(){
    calculateArea();
    this.color = "Blue";
    print(pi);
    print(maxRadius);
  }
  
  
  static void linecode(){
    print("-------------------------------------");
  }
  
}
```

# Lambda 

```
void main(){
  
  Function addTwoNumbers = (int a,int b){
    var sum = a+b;
    print(sum);
  };
  
  
  var multiplyByFour = (int number){
    return number * 4;
  };
  
  
  Function addNumbers = (int a,int b) => print(a+b);
  
 
  Function addline = (String a) => print("________");
  
  var multiplyFour = (int number) => number*4;
  
  
  addTwoNumbers(2,5);
  addline("_________");
  print(multiplyByFour(5));
  addline("_________");
  addTwoNumbers(3,7);
  addline("_________");
  print(multiplyFour(10));  
 
}

void addMyNumbers(int a,int b){
  var sum = a+b;
  print(sum);
}
```
# High Order Funcion

```
void main(){
  
  Function addNumbers = (a,b) => print(a+b);
  someOtherFunction("Hello",addNumbers);
 
  
  Function addLine = ( String a) => print("____");
  
}


void someOtherFunction(String message,Function myFunction){
  print(message);
  myFunction(2,4);
}


Function taskToPerform(){
  Function multiplyFour = (int number) => number * 4;
    return multiplyFour;
}
```

# Callable Function

```
void main(){
  
  var personOne = Person();
  var msg = personOne(24,23);
  print(msg);
  
  var add = personOne(10,129);
  print(add);
}

class Person{
  //String call(int age,String name){
  //  return "The name of the person is $name and age is $age";
  // }
  
  int call(int a,int b){
    return a+b;
  }
}
```


