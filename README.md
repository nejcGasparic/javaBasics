# Osnove JAVE

* Ogrodje programa v Javi

```java
public class Program{ //ime razreda

    public static void main(String[]args){ //main metoda
    ...
    }
}
```

* PRINT metode
```java
System.out.print("Hello!"); // ne gre v nov odstavek

System.out.println("Hello!"); //gre v nov odstavek

System.out.printf("Hello!\n"); // \n, s tem določilom bomo skočili v novo vrstico
```
* Spremenljivke
    
```java
    //celoštevilske
    byte a = 1;
    short b = 2;
    int c = 3;
    long d = 4;

    //realnoštevilske
    double e = 1.0;
    float f = 2.0;

    //črkovne
    char crka = 'A';
    String beseda = "Hello";

    //izjavne
    boolean flag1 = true; //če je izjava pravilna
    boolean flag2 = false; //če je izjava lažna
```
* Operacije
    * __+__ seštevanje
    * __-__ odštevanje
    * __*__ množenje
    * __/__ deljenje
    * __%__ ostanek pri deljenju
```java
    int a = 6;
    int b = 3;
    System.out.println(a+b); //9
    System.out.println(a-b); //3
    System.out.println(a*b); //18
    System.out.println(a/b); //2
    System.out.println(a%b); //0
```

* Pogojni stavek

```java
    if(a < 3){
        //se izvede ta del kode
    }
    else if(a > 3){
        //če je a večji od 3 se izvede ta del
    }
    else{
        //ta del se bo izvedel, ko bo a = 3
        //lahko zapišemo tudi else if(a == 3){}
    }
```
* Primerjalni operatorji
    * __==__ enak kot
    * __<=__ manjši ali enak
    * __<__ manjši
    * __>=__ večji ali enak
    * __>__ večji
    * __!=__ različen od

* Logični operatorji

    * __&&__ logični in
    * __||__ logični ali
    * __!__ logična negacija

```java
//primeri
boolean a = true;
boolean b = false;

if(a && b){
    //ta del kode se ne prevede
    //saj je spremenljivka b false
}
else if(a || b){
    //ta del se prevede
    //saj je vsaj ena izmed spremenljivk true
}
else if(a){
    //se izvede
}
else if(b){
    //se ne izvede
    //saj b ni true
}
```

