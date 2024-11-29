# Proyecto: Sistema de Seguridad con Arduino
Entrega del proyecto final de Arquitecura Computacional

# Dependencias
- StateMachineLib
- AsyncTaskLib
- DHT 
- LiquidCrystal 
- Keypad

# Simulador del proyecto
A través de la plataforma wokwi, en el cual puedes probar el codigo y/o mirar las conexiones para probarlo en fisico: [Simulador](https://wokwi.com/projects/415921841071873025 "Simulador")

# El sistema permite: 
## Ingreso de usuarios:
Un usuario puede ingresar al sistema utilizando una clave secreta.

### Monitorear sensores: 
El sistema puede leer datos de sensores como temperatura, luminosidad y movimiento y mostrarlos en la pantalla LCD.

### Visualizar alarmas:
Si se detecta un valor fuera de rango en los sensores o algún movimiento inusual, el sistema activa una alarma visual (LED rojo) y sonora (buzzer) y muestra un mensaje en la pantalla LCD.

### Bloqueo por intentos fallidos:
Si un usuario ingresa la clave incorrecta varias veces, el sistema se bloquea y requiere un reinicio.

# Bosquejo de sistema
![image]()

# Integrantes
1. Gloria Valentina Idrobo Montenegro
2. Jhon Alexander Ramirez Anacona
3. Maria Paula Barrera Muñoz
