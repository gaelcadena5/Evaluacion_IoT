# Evaluacion_IoT

# Evaluación Primer Parcial

## Universidad Modelo  
*Carrera:* Ingeniería en Desarrollo de Tecnología y Software  
*Materia:* Internet de las Cosas  
*Alumno:* Joaquín Casillas González  

---

## Proyecto: Monitoreo de Temperatura con Raspberry Pi Pico W

### Descripción
Este proyecto ha sido desarrollado como parte de la materia Internet de las Cosas. Consiste en programar una *Raspberry Pi Pico W* para medir la temperatura utilizando su sensor interno y enviar los datos a un canal de *ThingSpeak* para su monitoreo y análisis en tiempo real.

### Tecnologías y Herramientas
- *Hardware:* Raspberry Pi Pico W
- *Lenguaje de Programación:* MicroPython
- *Plataforma IoT:* ThingSpeak
- *Conexión:* WiFi
- *Software de visualización:* MATLAB

### Objetivos
- Capturar la temperatura utilizando el sensor interno de la Raspberry Pi Pico W.  
- Programar la tarjeta con MicroPython para procesar los datos.  
- Enviar la información de temperatura a ThingSpeak en tiempo real.  
- Visualizar y analizar los datos en la nube.  
- Implementar funciones en MATLAB para calcular el promedio de los últimos 10 datos y generar una alerta si la temperatura supera los 35°C.

### Pasos Realizados
1. *Configurar el intérprete MicroPython y la Raspberry Pi Pico W en Thonny.*
2. *Crear el código para medir la temperatura y enviarla a ThingSpeak:*

```python
  
```

3. *Utilizar ThingSpeak para visualizar los datos en tiempo real.*
4. *Desarrollar en MATLAB:*
   - Una función que calcula el promedio de los últimos 10 datos registrados.
   - Una función que genera una alerta si la temperatura supera los 35°C.

### Instalación y Uso
1. *Clonar el repositorio:*  
   ```bash
   git clone https://github.com/Joaquower/Evaluaci-nParcial.git
   cd Evaluaci-nParcial
   ```
2. *Instalar MicroPython en la Raspberry Pi Pico W.*
3. *Conectar.*
4. *Crear un canal en ThingSpeak:*  
   - Acceder a ThingSpeak y crear un nuevo canal.
   - Obtener el Channel ID y la Write API Key.
5. *Subir el código a la Raspberry Pi Pico W* usando *Thonny* o un entorno compatible.
6. *Configurar las credenciales WiFi y el canal de ThingSpeak* en el código.
7. *Ejecutar el script y visualizar los datos en la nube.*

### Estructura del Repositorio
```
Proyecto-IoT-Temperatura
│── src/                # Código fuente del proyecto
│── docs/               # Documentación adicional
│── assets/             # Imágenes y gráficos
│── README.md           # Documentación principal
```

### Vista Previa
(Agrega capturas de pantalla o diagramas del proyecto aquí)

### Créditos
*Autor:* Joaquín Casillas González  
*Universidad:* Universidad Modelo  
*Materia:* Internet de las Cosas  

Para consultas o dudas, contáctame en [joaquin.casillas02@gmail.com].

---
Proyecto realizado para la Evaluación del Primer Parcial
