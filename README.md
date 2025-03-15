# TP 1 Cronómetro Binario  

## Descripción  
Este proyecto es una implementación de un **cronómetro binario** desarrollado en **C/C++ para Arduino**. Utiliza LEDs para representar valores en binario y permite iniciar, pausar y reiniciar el conteo con botones físicos. El control del tiempo se maneja con la función `millis()` para asegurar una transición perceptible de los LEDs.  

## Funcionalidades  

- **Visualización en Binario:**  
  - Representación del tiempo en binario mediante LEDs de distintos colores.  
  - Apagado y encendido de LEDs según la progresión del cronómetro.  

- **Control del Cronómetro:**  
  - **Botón START:** Inicia la secuencia del cronómetro.  
  - **Botón PAUSA:** Detiene la secuencia sin reiniciarla.  
  - **Botón RESET:** Reinicia el cronómetro y vuelve al estado inicial.  

- **Gestión de LEDs:**  
  - Modularización del código para el control de LEDs.  
  - Cambio de estado de los LEDs cada segundo.  
  - Apagado de LEDs previos al avanzar en la secuencia.  

# TP 2 Juego del Ahorcado 

## Descripción  
Este proyecto implementa el clásico **Juego del Ahorcado** en una placa **Arduino**, utilizando un **LCD 16x2** y botones físicos para la interacción. El juego permite seleccionar letras, verificar si están en la palabra secreta y gestionar las vidas restantes. Además, muestra una representación visual del ahorcado cuando el jugador pierde.  

## Funcionalidades  

- **Selección de Letras:**  
  - Navegación por el abecedario con botones "Siguiente" y "Anterior".  
  - Selección de una letra con el botón "Seleccionar".  
  - Registro de letras ingresadas para evitar repeticiones.  

- **Verificación de la Palabra:**  
  - Comparación de la letra seleccionada con la palabra secreta.  
  - Actualización de la palabra oculta con letras correctas.  
  - Reducción de vidas si la letra ingresada es incorrecta.  

- **Gestión del Juego:**  
  - Visualización del estado actual de la palabra oculta en el **LCD 16x2**.  
  - Indicación de las vidas restantes con iconos en el display.  
  - Representación gráfica del ahorcado en caso de perder la partida.  
  - Reinicio automático tras 3 segundos al finalizar el juego.  

