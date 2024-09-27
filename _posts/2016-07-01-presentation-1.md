---
title: Actuadores
layout: post
permalink: /actuadores/
background: '#0a5'
slides:
 - title: Actuadores Eléctricos - Tipos
   slide-data: |
     - **Motores eléctricos:** Convierte la energía eléctrica en movimiento rotativo o lineal.
     - **Actuadores lineales eléctricos:** Utilizan un motor para mover un husillo y generar movimiento lineal.
     - **Solenoides:** Generan movimiento lineal a partir de un campo magnético inducido por corriente.
     
 - title: Actuadores Eléctricos - Funcionamiento
   slide-data: |
     Los actuadores eléctricos convierten la energía eléctrica en movimiento mecánico. Un motor eléctrico, por ejemplo, convierte la energía en movimiento rotativo, mientras que los actuadores lineales convierten esta rotación en desplazamiento lineal a través de husillos o sistemas de engranajes.

 - title: Actuadores Eléctricos - Características
   slide-data: |
     - **Precisión:** Alta precisión en el control de la posición y velocidad.
     - **Control:** Fácil de integrar con sistemas de control mediante señales eléctricas.
     - **Requiere electricidad:** Depende completamente de la alimentación eléctrica.
     - **Eficiencia:** Alta eficiencia en la conversión de energía eléctrica a movimiento mecánico.

 - title: Actuadores Eléctricos - Modo de Comunicación
   slide-data: |
     - **Señales PWM:** Usado para controlar la velocidad y posición.
     - **Señales digitales o analógicas:** Para encender/apagar o controlar la fuerza/velocidad.
     - **Protocolos de comunicación:** Modbus, CANopen, Profibus, etc.

 - title: Actuadores Mecánicos - Tipos
   slide-data: |
     - **Actuadores de leva:** Utilizan una leva para convertir el movimiento rotativo en lineal.
     - **Engranajes y cadenas:** Convierte movimiento rotativo en otro movimiento rotativo o lineal mediante transmisión mecánica.
     - **Muelles:** Almacenan energía mecánica y la liberan para generar movimiento.

 - title: Actuadores Mecánicos - Funcionamiento
   slide-data: |
     Los actuadores mecánicos funcionan por medio de componentes como levas, engranajes o sistemas de transmisión para transformar movimiento o almacenar energía.

 - title: Actuadores Mecánicos - Características
   slide-data: |
     - **Durabilidad:** Alta resistencia al desgaste y larga vida útil.
     - **No requiere electricidad:** Funciona sin energía eléctrica, utilizando energía mecánica acumulada.
     - **Fiabilidad:** Muy fiables en condiciones extremas.
     - **Velocidad:** Pueden operar a altas velocidades dependiendo del diseño mecánico.

 - title: Actuadores Mecánicos - Modo de Comunicación
   slide-data: |
     - **Sistemas mecánicos:** No requieren modos electrónicos de comunicación.
     - **Sistemas de palancas o levas:** Transmiten el movimiento manual o automático.

 - title: Actuadores Hidráulicos - Tipos
   slide-data: |
     - **Cilindros hidráulicos:** Producen movimiento lineal mediante la presión de un fluido.
     - **Motores hidráulicos:** Convierte la presión hidráulica en movimiento rotativo.
     - **Válvulas hidráulicas:** Controlan el flujo y la presión del fluido para activar el movimiento.

 - title: Actuadores Hidráulicos - Funcionamiento
   slide-data: |
     Los actuadores hidráulicos funcionan mediante la presión de un fluido (generalmente aceite) para generar movimiento. En un cilindro hidráulico, el fluido presurizado empuja un pistón para generar movimiento lineal.

 - title: Actuadores Hidráulicos - Características
   slide-data: |
     - **Fuerza:** Capaces de generar grandes cantidades de fuerza con tamaño compacto.
     - **Precisión limitada:** Menos precisos que los actuadores eléctricos.
     - **Requiere mantenimiento:** Sistema cerrado con control de fugas y mantenimiento de fluidos.
     - **Velocidad:** Ofrecen un amplio rango de velocidad.

 - title: Actuadores Hidráulicos - Modo de Comunicación
   slide-data: |
     - **Control de válvulas:** Usan válvulas hidráulicas para regular el flujo y la presión.
     - **Sistemas de retroalimentación:** A veces integran sensores para retroalimentación sobre la posición o fuerza aplicada.
     - **Control mediante señales eléctricas:** Aunque son hidráulicos, la comunicación puede realizarse electrónicamente para sistemas automatizados.
---

{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1>{{ slide.slide-data }}</section>
                    
{% endfor %}
