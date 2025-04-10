---
tags: "#java"
created: "2025-04-06 20:21:37"
---
## **Definition**
La estructura switch case permite permite ejecutar el bloque de código que coincide con el valor del case. Se utiliza cuando hay una gran cantidad valores a evaluar.
___
## **Key concepts**
### **Case**
Contiene un valor que si coincide con el evaluado en el switch ejecuta el bloque que tiene en su interior.

### **Default**
Ejecuta el bloque de código si el valor evaluado no coincide ningún case. Es opcional, parecido a un else.

### **Break**
Detiene la ejecución del bloque donde se encuentra y continúa ejecutándose fuera del mismo.

### **Facts**
- Se puede almacenar el valor evaluado por el switch en una variable utilizando -> para devolverlo.
___

## **Examples**
```java
import java.util.Scanner;  
  
public class ifConditional {  
    public static void main(String[] args) {  
        Scanner input = new Scanner(System.in);  
        System.out.println("Introduce el número del día de la semana: ");  
        int dayNum = input.nextInt();  
  
        switch (dayNum) {  
            case 1:  
                System.out.println("Lunes");  
                break;  
            case 2:  
                System.out.println("Martes");  
                break;  
            case 3:  
                System.out.println("Miércoles");  
                break;  
            case 4:  
                System.out.println("Jueves");  
                break;  
            case 5:  
                System.out.println("Viernes");  
                break;  
            case 6:  
                System.out.println("Sábado");  
                break;  
            case 7:  
                System.out.println("Domingo");  
                break;  
            default:  
                System.out.println("No existe");  
        }  
  
  
  
    }  
}
```
___
## **Connections**
**Derivative from [[If block]] 


