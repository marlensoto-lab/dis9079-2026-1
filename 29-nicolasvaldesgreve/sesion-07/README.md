# sesion-07

# Apuntes 20/04

Se nos entregó un potenciómetro B20k, un LDR, una protoboard nueva, un motor Micro Servo 9g.

Es primera vez que veo éste motor, por lo que no entendía muy bien cómo funcionaba hasta que Aarón nos explicó que éste motor tiene tres terminales:

1. Alimentación (cable rojo)
2. Tierra (cable café)
3. Comunicación (cable amarillo)

Para poder explicar cómo ubicar los componentes dentro de la protoboard, Aarón fue mostrando paso a paso qué hacer dentro de TinkerCAD en el cual se puede hacer una simulación de circuitos!! muy buena herramienta.

En TinkerCAD, Aarón nos dijo que para conenctar el Arduino UNO R4 WiFi teníamos que conectar la alimentación en el pin que se encuentra en la sección de ``power`` llamado ``5V``, mientras que para conectar a tierra tenemos que usar el pin de la sección ``power`` llamado ``GND`` o en la sección llamada ``digital`` que también tiene un pin llamado ``GND``. Para lograr que la placa Arduino UNO R4 WiFi se pueda comunicar con el potenciómetro, conectamos un cable dupont en el pin 2 del potenciómetro al pin ``A0`` de la placa que se encuentra en la sección de ``analog``, mientras que al potenciómetro se le conecta un cable para la alimentación y otro para tierra en los extremos de éste.

---

 Buscar cómo reemplazar el potenciómetro en el circuito por el LDR
