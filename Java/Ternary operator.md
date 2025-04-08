---
tags: "#java"
created: "2025-04-06 19:59:05"
---
## **Definition**
El operador ternario permite evaluar una condición y almacenar su resultado en una sola línea.
___
## **Key concepts**
### **Facts**
- Aunque sirva para evaluar condiciones no es una estructura de control, sino un operador.
___
## **Resources**
```java
import java.util.Scanner;  
  
public class ifConditional {  
    public static void main(String[] args) {  
        Scanner input = new Scanner(System.in);  
        System.out.println("Introduce tu edad: ");  
        int age = input.nextInt();  
  
        String isLegalAdult = age >= 18 ? "Es mayor" : "Es menor";  
        System.out.println(isLegalAdult);  
  
    }  
}
```
___
## Connections
**Similar to [[If block]]**