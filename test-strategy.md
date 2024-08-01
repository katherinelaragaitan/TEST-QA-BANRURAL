## estrategia de pruebas

### errores encontrados y correcciones

1. **error**:   const ATTEMPS = 5; el valor de la constante es incorrecta
    - **solucion**:  ajustar la constante a 10
      const ATTEMPS = 10;
2. **error**:     let randomNumber = Math.random() * 10; el valor aleatorio es incorrecto
    - **solucion**:  ajustar ajustar el valor aleatorio a 100
  Math.floor(Math.random() * 100) + 1;
3. **error**:  Verificacion de numero entero 
    - **solucion**:  validar utilizando Number.isInteger;
4. **error**:  errores tipograficos y de selector
    - **solucion**:  corregir a: `addEventListener` y `document.querySelector('.lowOrHi')`;
5. **error**:   la logica estaba invertida en los mensajes de acierto y error 
    - **solucion**:  intercambiar los mensajes de acierto y error
6. **error**:   estilos incorrectos pera los mensajes
    - **solucion**:  añadir clases CSS con los colores correctos y aplicarlos correctamente con JavaScript; 

Esto se realizo siguiendo los requerimientos dados asi como tambien los recursos sugeridos y el uso de la consola del navegador. 