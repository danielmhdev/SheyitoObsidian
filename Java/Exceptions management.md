---
tags: "#java"
created: "2025-04-09 09:58:26"
---
## **Definition**
Las excepciones son errores controlables durante la ejecución de un programa y es imprescindible manejarlas de forma eficiente para que el código funcione correctamente. 
___
## **Key concepts**
### **Purpose**
- Evitar que un programa se bloquee de forma inesperada.
- Proporcionar al usuario una respuesta clara del error
- Permitir que el programa siga ejecutándose
- Asegurarse de que los recursos (archivos, conexiones etc) se cierren correctamente aún con fallos.

### **Checked exceptions**
Excepciones que surgen cuando el compilador obliga a manejar posibles excepciones futuras.

### **Unchecked exceptions**
Excepciones que surgen cuando depende del programador manejarlas o no porque el compilador no te obliga a hacerlo.

### **Custom exceptions**
Excepciones creadas por el propio programador para lanzar errores intencionalmente.

### **Errors**
Los errores no son excepciones. Estos representan consecuencias graves en el sistema o el JVM y no pueden manejarse.
___
## **Example**
```java
try {
	int x = 10/0
} catch (ArithmeticException e) {
	System.out.println("Error: división entre cero")
} finally {
	System.out.println("Esto se ejecutará siempre")
}
```


