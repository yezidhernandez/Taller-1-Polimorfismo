# Taller-1-Polimorfismo
## 📊 Sustento de las pruebas

Se implementaron pruebas unitarias para la clase `Circle` utilizando **JUnit 5** con el fin de verificar el correcto funcionamiento de los métodos `calculateArea()` y `calculatePerimeter()`.  

Anteriormente, el test validaba únicamente un valor de radio, lo que limitaba la cobertura.  
En la versión actual se ampliaron los casos de prueba para incluir:

1. **Casos normales**: Radios positivos (1 y 2.3) para validar cálculos típicos.
2. **Caso límite**: Radio igual a 0, asegurando que el resultado sea 0 tanto en área como en perímetro.
3. **Verificación de mutadores**: Se comprobó que `setRadio()` modifica el valor y que `getRadio()` lo retorna correctamente, además de validar el área después del cambio.

Todas las pruebas fueron ejecutadas en **NetBeans**, obteniendo resultados correctos (100% de pruebas en verde), lo que confirma que la implementación de la clase `Circle` es consistente y cumple con los requerimientos.

## 👨‍💻 Autores
- **Yezid Hernández** 
- **Dayana Portilla** 
