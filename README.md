# Dart_Tutorial

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





