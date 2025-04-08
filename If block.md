---
tags: "#java"
created: "2025-04-06 18:55:29"
---
## **Definition**
La estructura `if` permite ejecutar un bloque de código solo cuando se cumple una condición.

___
## **Key concepts**

### **`else` block**
Define una alternativa cuando la condición del `if` no se cumple.  
### **`else if` block**
Permite evaluar condiciones adicionales en orden, antes de llegar al `else`.
___
## **Resources**
```java
import java.util.Scanner;  
  
public class ifConditional {  
    public static void main(String[] args) {  
        Scanner input = new Scanner(System.in);  
        System.out.println("Introduce tu edad: ");  
        int age = input.nextInt();  
  
        if (age >= 18) {  
            System.out.println("Eres mayor de edad");  
        }  
        else {  
            System.out.println("Eres menor de edad");  
        }  
    }  
}
```