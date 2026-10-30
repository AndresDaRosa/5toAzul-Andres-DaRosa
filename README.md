# 5toAzul-Andres-DaRosa
Pensamiento Computacional
Clase del 24/09 creación del github

1era actividad: el problema de la arepera

1. Encuentra el patrón que sigue el precio. ¿Cuánto aumenta por cada arepa adicional?
   
​2. Escribe una fórmula matemática que relacione la cantidad de arepas (n) con el precio total (P).

​3. Usa la fórmula para predecir el precio de 10 arepas.

​4. Si el precio de la primera arepa es "a" y el descuento por volumen sigue la misma lógica, escribe una fórmula general para cualquier cantidad n.

​5. ¿Por qué el precio no aumenta siempre lo mismo? ¿Qué pasaría si el patrón cambiara?

<img width="1956" height="2704" alt="1000029757" src="https://github.com/user-attachments/assets/e90f5fa1-58fc-446a-a26f-a62256e1f81a" />
<img width="1864" height="2632" alt="1000029756" src="https://github.com/user-attachments/assets/48555d98-f666-4461-b26e-0f9fd1ff39f8" />

Tinkercad account:

user: andres.darosa

password: Andresdarosa1234*


Foto del primer circuito de tinkercad:

<img width="1382" height="756" alt="image" src="https://github.com/user-attachments/assets/669246a5-534f-4f9c-9f65-000a6402ab55" />

Foto del código del primer circuito de tinkercad:

<img width="928" height="751" alt="image" src="https://github.com/user-attachments/assets/2157893f-b68d-402c-9ad3-9d9e0a7a7e09" />
<img width="937" height="751" alt="image" src="https://github.com/user-attachments/assets/0025ab38-af3e-494b-b1fa-8220e366f510" />

link del trabajo del circuito: https://www.tinkercad.com/things/dyhUGHN2GQ7-frantic-jaban/editel?returnTo=https%3A%2F%2Fwww.tinkercad.com%2Fdashboard&sharecode=HYLSVOBN1-9HhEP3Gl23OFs7qoFyHZOzWnKjxi57w-Y

resolución del problema escrito de distancia ccs-maracaiboÑ

<img width="1080" height="830" alt="image" src="https://github.com/user-attachments/assets/22124f36-6731-4fd2-b950-06cddf2425bc" />

Actividad 15-10-26
Circuito sencillo para resolver un problema cotidiano: Cruce de peatones en las calles

¿Cuál es el problema?
El peligro y la falta de seguridad que enfrentan los peatones al intentar cruzar una calle con tráfico vehicular continuo, donde no hay un control claro del paso.

¿Quién se beneficiaría de la solución?
Los peatones (especialmente estudiantes, niños y adultos mayores) al poder cruzar de manera segura, y también los conductores, ya que se organiza el flujo vehicular de forma ordenada.

¿Cómo ayudará tu prototipo a resolver la situación?
Permite que el peatón solicite el paso mediante un botón. El sistema detiene a los vehículos de forma controlada (pasando de verde a amarillo intermitente y luego a rojo) y enciende una luz verde exclusiva para que los peatones crucen tranquilos.

circuito:
<img width="1027" height="757" alt="image" src="https://github.com/user-attachments/assets/9846bfa3-1be8-4cd3-a376-7ae7623e3695" />

<img width="760" height="743" alt="image" src="https://github.com/user-attachments/assets/3b4fa71e-8c4d-4371-aa82-aafe4f955d17" />
<img width="760" height="792" alt="image" src="https://github.com/user-attachments/assets/716d65c8-ebd0-4aab-bb39-dc2fde816fb5" />
<img width="758" height="360" alt="image" src="https://github.com/user-attachments/assets/4ca6197c-6707-4adc-8218-8abe657bd71d" />


# Actividad del 22-10

📄(Actividad_del_22-10.pdf)

---

## Tarea #1

### Actividad 1

**La llegada de estudiantes:** Los estudiantes llegan al centro en momentos impredecibles y sin un orden fijo. El sistema debe detectar cada llegada y anotar la hora exacta, porque de ella depende el orden de atención y el cálculo del tiempo de espera.

**El registro:** Al llegar, cada estudiante se identifica e indica qué trámite necesita: entrega de documentos, solicitud de constancia o consulta general. También se verifica que no haya pasado la hora de cierre y que traiga los documentos completos. Si todo está en orden, recibe un número de turno.

**Las prioridades:** En este paso se decide si el estudiante es un caso prioritario, por ejemplo, por discapacidad, embarazo o salud. Los prioritarios entran a la cola prioritaria y los demás a la cola normal. Ambas colas respetan el orden de llegada.

**La atención:** Cada vez que la ventanilla queda libre, se elige al siguiente estudiante según las reglas de prioridad, sin que nadie espere indefinidamente. Luego se le llama, se atiende su trámite y se registran la hora de inicio y la hora de fin. Si no se presenta a tiempo, se marca como ausente.

**El cierre:** Al llegar la hora de cierre ya no se registran nuevos estudiantes, pero se atiende a todos los que estaban en fila. Al final se calcula el tiempo promedio de espera y se muestran los resultados, para evaluar si el sistema realmente redujo la espera.

### Actividad 2

Para definir cada dato nosotros vamos a hacer una tabla de datos que explicará todos los datos de los estudiantes:

| Dato | Tipo de dato | Para qué sirve | Ejemplo |
|---|---|---|---|
| numeroTurno | Entero | Identificar y llamar al estudiante en orden | 15 |
| codigoEstudiante | Texto | Identificar al estudiante (cédula o código) | V-30123456 |
| nombre | Texto | Llamarlo y dejar registro de la atención | Samuel Gil |
| tipoTramite | Lista (ENTREGA, CONSTANCIA, CONSULTA) | Saber qué trámite hará y estimar su duración | CONSTANCIA |
| tiempoEstimado | Entero (minutos) | Calcular el tiempo aproximado de espera | 10 |
| esPrioritario | Lógico (Verdadero/Falso) | Decidir si entra a la cola prioritaria o a la normal | Falso |
| motivoPrioridad | Texto | Justificar por qué es un caso prioritario | Ninguno |
| horaLlegada | Hora | Respetar el orden de llegada y medir la espera | 08:15 |
| documentosCompletos | Lógico (Verdadero/Falso) | Verificar en el registro que trae todo lo necesario | Verdadero |
| horaInicioAtencion | Hora | Calcular el tiempo de espera (inicio − llegada) | 08:40 |
| horaFinAtencion | Hora | Calcular cuánto duró realmente el trámite | 08:50 |
| estado | Lista (EN_ESPERA, EN_ATENCION, ATENDIDO, AUSENTE) | Hacer seguimiento de la situación del estudiante | ATENDIDO |

### Actividad 3

En esta actividad nosotros realizamos un diagrama de flujo para responder la actividad.

![Diagrama de flujo de la atención en ventanilla](Diagrama_de_flujo_atencion.png)

### Actividad 4

Usaría dos colas, una prioritaria y una normal, y en cada una se atiende por orden de llegada. Son prioritarios los estudiantes con discapacidad, las embarazadas, quienes tienen alguna condición de salud y quienes tienen un plazo que vence ese día. Elegí estos criterios porque son objetivos y verificables, no dependen de la opinión del personal.

No usé el método de atender primero los trámites más cortos porque, aunque reduce la espera promedio, rompe el orden de llegada y podría dejar a alguien esperando indefinidamente.

Para que el sistema sea justo, después de atender a dos prioritarios seguidos se atiende a uno normal, y si un estudiante normal lleva más de 30 minutos esperando, pasa de inmediato.

La espera se reduce sin alterar el orden: se verifican los documentos en el registro, se marca como ausente a quien no se presenta en tres minutos y se registra cuánto tarda cada trámite. Así se equilibran la equidad y la eficiencia.

---

## Tarea #2

### La optimización de la ruta del autobús escolar

#### 1. Representación de paradas y distancias

**Cantidad de estudiantes por parada:**

| Parada | Estudiantes |
|---|---|
| P1 | 4 |
| P2 | 3 |
| P3 | 6 |
| P4 | 2 |
| P5 | 5 |
| P6 | 3 |

**Matriz de distancias (en kilómetros):**

| Parada | P1 | P2 | P3 | P4 | P5 | P6 |
|---|---|---|---|---|---|---|
| **P1** | 0 | 2 | 5 | 7 | 10 | 3 |
| **P2** | 2 | 0 | 3 | 6 | 9 | 4 |
| **P3** | 5 | 3 | 0 | 4 | 7 | 6 |
| **P4** | 7 | 6 | 4 | 0 | 3 | 8 |
| **P5** | 10 | 9 | 7 | 3 | 0 | 11 |
| **P6** | 3 | 4 | 6 | 8 | 11 | 0 |

#### 2. Algoritmo paso a paso (algoritmo del vecino más cercano)

1. **Paso 1:** Definir el punto de partida (por ejemplo, la parada P1) y marcarla como visitada.
2. **Paso 2:** Desde la parada actual, revisar las paradas no visitadas y seleccionar aquella que se encuentre a la menor distancia.
3. **Paso 3:** Desplazarse a esa parada, registrarla como visitada y sumar los estudiantes a bordo.
4. **Paso 4:** Repetir los pasos 2 y 3 hasta que todas las paradas hayan sido visitadas.

#### 3. Aplicación del algoritmo y ruta propuesta

Partiendo de P1:

- Desde P1, la más cercana es P2 (2 km). (Estudiantes acumulados: 4 + 3 = 7)
- Desde P2, la más cercana no visitada es P3 (3 km). (Estudiantes acumulados: 7 + 6 = 13)
- Desde P3, la más cercana no visitada es P4 (4 km). (Estudiantes acumulados: 13 + 2 = 15)
- Desde P4, la más cercana no visitada es P5 (3 km). (Estudiantes acumulados: 15 + 5 = 20)
- Desde P5, la única parada restante es P6 (11 km, aunque en un circuito real se optimizaría con el colegio, aquí cerramos con la última parada). (Estudiantes acumulados: 20 + 3 = 23)

**Ruta propuesta:** P1 → P2 → P3 → P4 → P5 → P6

**Distancia total:** 2 + 3 + 4 + 3 + 11 = 23 km

#### 4. Comparación con una alternativa

**Alternativa (ruta secuencial ordenada):** P1 → P2 → P3 → P6 → P4 → P5

**Distancia:** P1 → P2 (2) + P2 → P3 (3) + P3 → P6 (6) + P6 → P4 (8) + P4 → P5 (3) = 22 km

**Criterio elegido:** Menor distancia total.

**Conclusión:** Aunque la alternativa secuencial resulta ligeramente menor en distancia total (22 km frente a 23 km), el algoritmo del vecino más cercano suele ser más eficiente en tiempo real para evitar desvíos bruscos, aunque en este caso específico la alternativa directa ofrece un ahorro de 1 km.

---

## Tarea #3

### 1. Errores y limitaciones

1. **No calcula el promedio.** Solo suma las notas y no divide entre 3, así que un estudiante con 25, 20 y 30 (promedio real 25) aparece como aprobado porque la suma da 75.
2. **No valida las notas.** Acepta valores imposibles, como −10 o 150, que alteran el resultado. Un estudiante con 150, 10 y 20 "aprobaría".
3. **No muestra el promedio.** El estudiante solo ve "Aprueba" o "No aprueba", sin saber con cuánto.
4. **Usa `=` para asignar.** Se confunde con una comparación. En pseudocódigo lo correcto es usar `←`.

### 2. Pseudocódigo corregido

```
Inicio
   Leer nota1, nota2, nota3
   promedio ← (nota1 + nota2 + nota3) / 3
   Si promedio >= 60 Entonces
      Escribir "Aprueba"
   SiNo
      Escribir "No aprueba"
   FinSi
Fin
```

Los paréntesis son necesarios para que se sumen las tres notas antes de dividir.

### 3. Con validación de 0 a 100

```
Inicio
   suma ← 0
   Para i ← 1 Hasta 3 Hacer
      Escribir "Ingrese la nota ", i, ":"
      Leer nota
      Mientras nota < 0 O nota > 100 Hacer
         Escribir "Nota inválida. Debe estar entre 0 y 100:"
         Leer nota
      FinMientras
      suma ← suma + nota
   FinPara
   promedio ← suma / 3
   Si promedio >= 60 Entonces
      Escribir "Aprueba"
   SiNo
      Escribir "No aprueba"
   FinSi
Fin
```

El ciclo `Mientras` vuelve a pedir la nota hasta que sea válida, así ningún valor fuera de rango entra al cálculo.

### 4. Mejora adicional

La propuesta es mostrar el promedio, indicar si el estudiante debe ir a recuperación y permitir elegir cuántas notas ingresar. Para la recuperación se supuso un rango de 40 a 59.

```
Inicio
   Escribir "¿Cuántas notas desea ingresar?"
   Leer cantidad
   Mientras cantidad < 1 Hacer
      Escribir "Debe ingresar al menos 1 nota:"
      Leer cantidad
   FinMientras
   suma ← 0
   Para i ← 1 Hasta cantidad Hacer
      Escribir "Ingrese la nota ", i, ":"
      Leer nota
      Mientras nota < 0 O nota > 100 Hacer
         Escribir "Nota inválida. Debe estar entre 0 y 100:"
         Leer nota
      FinMientras
      suma ← suma + nota
   FinPara
   promedio ← suma / cantidad
   Escribir "Promedio: ", promedio
   Si promedio >= 60 Entonces
      Escribir "Aprueba"
   SiNo
      Si promedio >= 40 Entonces
         Escribir "Debe presentar recuperación"
      SiNo
         Escribir "No aprueba"
      FinSi
   FinSi
Fin
```


Actividad 29/10/26

<img width="1255" height="743" alt="image" src="https://github.com/user-attachments/assets/d313459a-203a-475d-b545-a05b53ed87d2" />

<img width="977" height="728" alt="image" src="https://github.com/user-attachments/assets/5fd35b0e-6c95-47ac-a787-e8ba9489a413" />

<img width="980" height="723" alt="image" src="https://github.com/user-attachments/assets/59a61fd9-aa0e-4c21-8760-72aea5d5e31e" />

<img width="977" height="730" alt="image" src="https://github.com/user-attachments/assets/2d1df4f8-ac8f-49a4-9477-4f19ec659634" />

<img width="980" height="727" alt="image" src="https://github.com/user-attachments/assets/b4670e1e-bba6-4a19-ad51-6bfb224ed886" />

<img width="955" height="712" alt="image" src="https://github.com/user-attachments/assets/d91b6a84-9363-45bd-a4b4-a4b4bb3777a6" />

# Notas de la guía: Control de servomotores con Arduino

*Fuente: How to Control Servo Motors with Arduino – Complete Guide (HowToMechatronics)*
*https://howtomechatronics.com/how-it-works/how-servo-motors-work-how-to-control-servos-using-arduino/*

---

## a) Principio de funcionamiento de un servomotor

Un servomotor es un sistema de lazo cerrado. Mide su propia posición y la corrige hasta llegar al ángulo deseado. Un servo de hobby tiene cuatro componentes internos: un motor DC, una caja de engranajes, un potenciómetro y un circuito de control. El motor DC gira rápido pero con poco torque. Los engranajes reducen la velocidad a unos 60 RPM y aumentan la fuerza.

El potenciómetro está unido al eje de salida y entrega un voltaje proporcional al ángulo real. El circuito de control compara ese voltaje con la señal que recibe. Si hay diferencia, activa un puente H interno que gira el motor en el sentido necesario hasta que el error sea cero. En los servos industriales, en lugar de potenciómetro se usa un encoder de alta precisión.

La señal de control es un tren de pulsos a 50 Hz, es decir, un pulso cada 20 ms. El ancho del pulso determina el ángulo:

| Ancho del pulso | Ángulo |
|---|---|
| 1 ms | 0° |
| 1.5 ms | 90° |
| 2 ms | 180° |

Según la marca, estos valores pueden ir de 0.5 ms a 2.5 ms. Los servos estándar giran unos 180° porque tienen topes físicos. Los de 360° (rotación continua) no permiten controlar la posición, solo la velocidad y el sentido de giro.

## b) Conexiones básicas (alimentación, tierra y señal)

El servo tiene solo tres cables:

- **Marrón** → tierra (GND).
- **Rojo** (el del medio) → alimentación positiva (5 V).
- **Amarillo o naranja** → señal de control, que va a cualquier pin digital del Arduino.

Si el servo usa una fuente externa, la tierra del Arduino **debe unirse** a la tierra del servo. Sin esa referencia común, la señal no se interpreta correctamente.

La guía compara dos modelos populares:

- **SG90 (micro servo):** pesa 9 g y trabaja de 3.5 a 6 V. Consume unos 100–200 mA en movimiento y hasta unos 650 mA bloqueado.
- **MG996R:** tiene engranajes metálicos, alto torque (unos 10–13 kg·cm) y trabaja de 4.8 a 7.2 V. Consume de 500 a 900 mA en funcionamiento y hasta 2.5 A bloqueado. Por eso no se debe conectar directamente al Arduino.

## c) Control mediante programación en Arduino

La guía muestra primero cómo generar la señal "a mano", sin librería. Se pone el pin en HIGH durante el ancho del pulso y en LOW el resto de los 20 ms. Por ejemplo, para 90° con un pulso de 1450 µs, el pin queda 1450 µs en alto y 18 550 µs en bajo (20 000 − 1450).

Al probar su servo, el autor encontró estos valores reales:

| Ancho del pulso | Ángulo |
|---|---|
| 0.6 ms | 0° |
| 1.45 ms | 90° |
| 2.3 ms | 180° |

Esto muestra que cada servo debe calibrarse.

```cpp
void loop() {
  digitalWrite(9, HIGH);
  delayMicroseconds(1450);   // ancho del pulso -> ~90°
  digitalWrite(9, LOW);
  delayMicroseconds(18550);  // resto del periodo de 20 ms
}
```

## d) Uso de la librería Servo

La forma más práctica es usar la librería `Servo.h`. Los pasos son:

- Incluir la librería y crear un objeto `Servo`.
- Usar `attach(pin, min, max)` para indicar el pin y, opcionalmente, los anchos de pulso mínimo y máximo en microsegundos. Por defecto son 544 µs para 0° y 2400 µs para 180°.
- Usar `write(ángulo)` para mover el servo a cualquier posición entre 0° y 180°.

Si el servo no recorre todo el rango de 0 a 180°, se corrige ajustando esos valores min/max en `attach()`.

```cpp
#include <Servo.h>
Servo miServo;
void setup() { miServo.attach(9, 600, 2300); }
void loop() {
  miServo.write(0);   delay(1000);
  miServo.write(90);  delay(1000);
  miServo.write(180); delay(1000);
}
```

## e) Consideraciones para la alimentación de múltiples servomotores

El pin de 5 V del Arduino entrega solo unos 500 mA si se alimenta por USB, o hasta 1 A con el conector de alimentación. Un SG90 podría funcionar directo, pero el autor recomienda **siempre usar una fuente externa** para mayor estabilidad. Con varios servos o con el MG996R, la fuente externa es obligatoria. La guía usa una de 5 V a 2 A para un servo y de 5 V a 6 A para varios. El amperaje alto no daña nada: solo indica cuántos servos puede mover a la vez.

Un problema común es que el servo tiembla o reinicia el Arduino por los picos de corriente al arrancar. La solución es colocar un **capacitor de desacople entre GND y 5 V**, que aporta corriente extra en esos picos.

En cuanto a cantidad, la librería Servo controla:

- Hasta **12 servos** en la mayoría de las placas.
- Hasta **48 servos** en el Arduino Mega. El autor controló 22 servos en su robot hexápodo.

Para muchos servos, la guía presenta el driver **PCA9685**:

- Tiene 16 canales PWM de 12 bits (4096 pasos).
- Se comunica por I2C con solo dos pines.
- Tiene reloj propio, así que mueve los servos sin cargar al Arduino.
- Se pueden encadenar hasta 62 drivers, lo que en teoría permite 992 servos.
- Cada driver necesita su propia dirección (configurada con pads de soldadura) y también requiere fuente separada para los servos.

## f) Ejemplos de movimiento angular y control de posición

La guía incluye varios ejemplos:

- **Movimiento por posiciones fijas:** un servo pasa por 0°, 90°, 135° y 180° con pausas entre cada posición mediante `delay()`.
- **Varios servos con la librería:** se crea un objeto por servo (por ejemplo, en los pines 8 a 12) y se mueven todos juntos a 0°, luego a 90° y luego a 180°.
- **Con el PCA9685:** se configura la frecuencia a 50 Hz y se usan las funciones `setChannelPWM()` y `pwmForAngle()` para llevar cada canal al ángulo deseado. Como cada servo responde un poco distinto, se calibra individualmente, incluso ajustando su punto de 90°.

Las aplicaciones mencionadas incluyen brazos robóticos, robots hexápodos, robots SCARA y modelos RC.




