# Informe-Tarea-9


1. OBJETIVOS

OBJETIVOS GENERALES


OBJETIVOS ESPECÍFICOS

2. MARCO TEÓRICO


3. RESOLUCIÓN DE EJERCICIOS:

PARTE 1: CIRCUITOS EN SERIE

SECCIÓN 17–1 Impedancia de circuitos RLC en serie


2. Determine la impedancia en la figura 17-59 y exprésela en forma polar

![image](https://user-images.githubusercontent.com/116771507/221469811-6b0122bf-b8e3-4933-8a2e-cecbbbf4747f.png)

Z=√(R^2+(XL-Xc)^2)

Z=√((47Ω)^2+(80Ω-35Ω)^2)= 65.1Ω


4. Para el circuito de la figura 17-59, determine la reactancia neta que hará que la magnitud de la impedancia sea igual a 100 Ω.

![image](https://user-images.githubusercontent.com/116771507/221470049-1ad82bab-be0b-49e6-a73f-b23944c41630.png)

Z=√(R^2+(XL-Xc)^2)= 100Ω

Z=√((47Ω)^2+(x)^2)

(47Ω)^2+(x)^2=(100Ω)^2

(x)^2= (100Ω)^2-(47Ω)^2

x = √((100Ω)^2-(47Ω)^2)= 88.27Ω


SECCIÓN 17–2 Análisis de circuitos RLC en serie.

6. Trace el diagrama fasorial de voltaje para el circuito de la figura 17-59.

![image](https://user-images.githubusercontent.com/116771507/221470101-8a362652-99c7-4e7a-a42f-b3a56fd0d357.png)

Z=√(R^2+(XL-Xc)^2)

Z=√((47Ω)^2+(80Ω-35Ω)^2) = 65.1Ω

I= Vs/Z= 4V/65.1Ω = 61.4 mA

VR= I x R = (61.4 mA) (47 Ω) = 2.89V

VL= I x XL = (61.4 mA) (80 Ω) = 4.91V

VC= I x Xc = (61.4 mA) (35 Ω) = 2.15V

θ= arctan(X/R) 

θ= arctan(45Ω/47Ω) = 43.8°

![image](https://user-images.githubusercontent.com/116771507/221473105-41ee79bf-906d-4ece-a6e5-bf06973f551b.png)


SECCIÓN 17–3 Resonancia en serie

8. Para el circuito de la figura 17-59, ¿es la frecuencia resonante más alta o más baja que el valor indicado por los valores de reactancia?

![image](https://user-images.githubusercontent.com/116771507/221470193-b1c9e45f-1a07-4d1f-bb3e-b078f4ab9b29.png)

10. En la figura 17-61, determine XL, XC, Z e I a la frecuencia resonante.

![image](https://user-images.githubusercontent.com/116771507/221470248-e24182e8-2a9b-48d0-9de3-de981ee82e33.png)

fr = 1/(2π√LC)

fr = 1/(2π√(1mH x 47uF))= 734 KHz

XL = 2π x fr x L 

XL= 2π (1mH) (734KHz) = 4.61 Ω

Xc= XL = 4.61 Ω

Z = R = 22Ω

I = Vs/Z = 12V/22Ω = 54.5 mA

12. Para el circuito RLC de la figura 17-62, determine la frecuencia resonante.

![image](https://user-images.githubusercontent.com/116771507/221470289-f308e4b9-61e3-4d6a-baf8-ca989dfe6812.png)


I = Vs/Z = 7.07V/10Ω = 7.07 mA


14. En la figura 17-62, determine el ángulo de fase entre el voltaje aplicado y la corriente a las frecuencias críticas. ¿Cuál es el ángulo de fase en condición de resonancia?

![image](https://user-images.githubusercontent.com/116771507/221470319-baf6fc22-f686-4552-9349-4d7c7ae9143e.png)

fr = 1/(2π√(8 uH x 0.015uF)) = 459 KHz

XL= 2π (8 uH) (459KHz) = 23.07 Ω

θ= arctan(X/R) = arctan(23.07Ω/10Ω) = 66.57°


PARTE 2: CIRCUITOS EN PARALELO

SECCIÓN 17–4 Impedancia de circuitos RLC en paralelo

16. Exprese en forma polar la impedancia del circuito de la figura 17-63.

![image](https://user-images.githubusercontent.com/116771507/221470365-c9a41da3-e2d0-462a-b926-c00e42d1eb8f.png)


I = Vs/z = 5V/100Ω = 50 mA = 50°


18. ¿A qué frecuencia el circuito de la figura 17-63 cambia su característica reactiva (de inductiva a capacitiva o viceversa)?

![image](https://user-images.githubusercontent.com/116771507/221470404-97c6c2f6-6bd3-4f88-96ce-fc5d6d35265d.png)

XL= 2π (15 mH) (12 KHz) = 1.13 KΩ

XL= 1/(2π (12 KHz) (0.022 uF)) = 603Ω


SECCIÓN 17–5 Análisis de circuitos RLC en paralelo

20. Determine la impedancia total del circuito de la figura 17-63 a 50 kHz. 

![image](https://user-images.githubusercontent.com/116771507/221470444-ea05f2b0-f741-43f0-a01a-b771b0a2be7f.png)


I = Vs/Z = 5V/100Ω = 50 mA


SECCIÓN 17–6 Resonancia en paralelo

22. ¿Cuál es la impedancia de un circuito resonante ideal dispuesto en paralelo (sin resistencia en las ramas)?

Zr es inmensamente grande

24. ¿Cuánta corriente se extrae de la fuente de la figura 17-64 en condición de resonancia? ¿Cuáles son las corrientes inductiva y capacitiva en la frecuencia resonante?

![image](https://user-images.githubusercontent.com/116771507/221470539-9eec3021-f2eb-4b94-95ae-11dd96ca0641.png)

fr = √(1-(Rw^2C)/L)/2π√LC 

fr = √(1-(((20Ω)^2 x (47pF))/50 mH)/2π√(50 mH x 47 pF)

fr = 104 KHz

XL = 2πfrL = 2π(104Hz)(50mH) = 32.6 Ω

Q = XL/Rw = 32.6kΩ/20Ω = 1630

Zr= 20Ω(1630^2 + 1) = 53.1 MΩ

Itot= Vs/Zr = 6.3V/53.1MΩ = 119 nA

Ic = IL = 6.3V/√((20Ω)^2 + (32.6Ω)^2) = 193 uA


PARTE 3: CIRCUITOS EN SERIE-PARALELO

SECCIÓN 17–7 ANÁLISIS DE CIRCUITOS RLC EN SERIE-PARALELO

26. Encuentre la impedancia total para cada circuito de la figura 17-65.

![image](https://user-images.githubusercontent.com/116771507/221470573-0f54612f-c186-47bb-803f-fbd6cba44708.png)


CIRCUITO A)

Q = XL/Rw = 100Ω/220Ω = 0.45

Zr= Rw(Q^2 + 1)

Zr= 220Ω(0.45^2 + 1) = 264.55Ω

CIRCUITO B)

Q = XL/Rw = 8KΩ/12KΩ = 0.67

Zr= Rw(Q^2 + 1)

Zr= 12KΩ(0.67^2 + 1) = 17.38 KΩ




28. Determine el voltaje entre las terminales de cada elemento mostrado en la figura 17-66, y expréselo en forma polar.

![image](https://user-images.githubusercontent.com/116771507/221470627-dc11f9fb-0318-4552-9176-fd252c4b3b68.png)

Xc = 1/2π(2KHz)(0.0047 uF) = 16.93 kΩ

XL = 2π(2KHz)(15 H) = 18.85Ω

IR1 = 12V/√((33kΩ)^2+(1.5H)^2) = 363 uA

IR2 = 12V/√((22kΩ)^2+(1.5H)^2) = 545 uA

VR1 = (363 uA)(33kΩ) = 1.93V

VR2 = (545 uA)(22kΩ) = 1.10V

VL = (363 uA)(18.85kΩ) = 6.84V

Vc = (545 uA)(16.93kΩ) = 2.13V


30. ¿Cuál es la corriente a través de R2 en la figura 17-67?

![image](https://user-images.githubusercontent.com/116771507/221470659-6bb408ae-c9f3-4c9a-939c-ec87d896a3f7.png)

IR2 = Vs/R2 = 115V/100Ω = 1.15 A

32. Determine la resistencia y la reactancia totales en la figura 17-68.

![image](https://user-images.githubusercontent.com/116771507/221470693-191376be-9084-48b9-be1a-61014ac0216b.png)

Xtot = 1/ (1/5KΩ + 1/10kΩ) = 3.33kΩ

Z = (100kΩ x 3.33kΩ)/√((10kΩ)^2+(3.33kΩ)^2) = 3.16kΩ

θ= arctan(X/R) = arctan(10kΩ/3.33kΩ) = 71.6°

RT= (3.16kΩ)cos(71.6°) = 997Ω

Xtot= (3.16kΩ)sin(71.6°) = 3kΩ

34. Determine si existe un valor de C que hará Vab=0V en la figura 17-69. Si no lo hay, explique la razón

![image](https://user-images.githubusercontent.com/116771507/221470780-f1516d2f-a735-488d-a497-d836f42681a8.png)

Vab = 0V ; Va = Vb

XL1= 2π(3 kHz)(12mH) = 226Ω

XL2= 2π(3 kHz)(8mH) = 151Ω

Va = VL1 = (226Ω / √((180Ω)^2+(226Ω)^2) x 12V = 9.38V

Vab no puede ser igual a 0V debido a que la rama LC no presenta la resistencia, por lo que el voltaje ab solo puede tener un ángulo de fase de 0°, 90° y -90°, por lo que Va no es igual que Vb en magnitud de ángulo de fase.

36. ¿Cuántas frecuencias resonantes hay en el circuito de la figura 17-70 ¿Por qué?

![image](https://user-images.githubusercontent.com/116771507/221470809-319eae68-5852-4fca-a7e1-c1c0e18f080c.png)

fr(paralelo) , fr(serie) ==> Hay dos frecuencias resonantes en el circuito debido a que se necesecita calcular la frecuencia resonante paralela y en serie.

 38. Diseñe un red resonante en paralelo usando una sola bobina y capacitores seleccionables mediante un interruptor para producir las siguientes frecuencias resonantes: 8 MHz, 9 MHz, 10 MHz, y 11 MHz. Suponga una bobina de 10 uH con resistencia de devanado de 5 Ω.

![image](https://user-images.githubusercontent.com/116771507/221476843-86bbd304-6b20-4bb6-917a-7463c615e12f.png)

C1 = 1 / (4 x π^2 x (8 MHz)^2 x (10uH)) = 40 pF

C2 = 1 / (4 x π^2 x (9 MHz)^2 x (10uH)) = 31 pF

C3 = 1 / (4 x π^2 x (10 MHz)^2 x (10uH)) = 25 pF

C4 = 1 / (4 x π^2 x (11 MHz)^2 x (10uH)) = 21 pF


PARTE 4: TEMAS ESPECIALES

SECCIÓN 17–8 Ancho de banda de circuitos resonantes

40. Si la frecuencia crítica baja es de 2400 Hz y la frecuencia crítica alta es de 2800 Hz, ¿cuál es el ancho de banda? ¿Cuál es la frecuencia resonante?

AB = 2800Hz - 2400Hz = 400Hz

fr = (2800Hz + 2400Hz)/2 = 2600 Hz


42. En un circuito tanque, ¿qué valores de L y C deberán utilizarse para obtener una frecuencia resonante de 8 kHz? El ancho de banda debe ser de 800 Hz. La resistencia de devanado del circuito es de 10 Ω.

C = 1/(π^2 x fr x Xc) = 1/(π^2 x (8kHz) x (100Ω)) = 1.98 uF

L = 1/(fr^2 x C (4π^2 + 0.025)) = 1/((8KHz)^2 x (1.98uF) (4π^2 + 0.025))

L= 1.99 uH

*CAPÍTULO 18*

SECCIÓN 18–1 Filtros pasabajas

2. Un filtro pasabajas tiene frecuencia crítica de 3 kHz. Determine a cuáles de las siguientes frecuencias se les permite pasar y cuáles son rechazadas:

a)100 Hz ==> Se le permite pasar.

b)1 kHz ==> Se le permite pasar.

c)2 KHz ==> Se le permite pasar.

d)3 KHz ==> Se le permite pasar.

e)5 KHz ==> Es rechazada.

4. ¿Cuál es fc para cada filtro mostrado en la figura 18-38? Determine el voltaje de salida a fc en cada caso cuando Vent= 5V.

![image](https://user-images.githubusercontent.com/116771507/221471253-e45918cd-210c-4ad4-8254-236e38cfcf58.png)

6. Determine la frecuencia crítica en cada una de las posiciones del interruptor en la red de filtros conmutados de la figura 18-40.

![image](https://user-images.githubusercontent.com/116771507/221471283-557ae6e8-1d30-458b-b05e-23e3b1ea3d6e.png)

8. En cada uno de los casos siguientes, exprese la relación de voltaje en dB:

a)Vent = 1V ;  Vsal = 1V

b)Vent = 5V ;  Vsal = 3V

c)Vent = 10V ;  Vsal = 7.07V

d)Vent = 25V ;  Vsal = 5V

10. Para cada filtro RC pasabajas, determine el voltaje de salida en dB con respecto a una entrada de 0 dB en las siguientes frecuencias (fc = 1 kHz):

a)10 KHz

b)100 KHz

c)1 MKz

SECCIÓN 18–2 Filtros pasaaltas

12. La frecuencia crítica de un filtro pasaaltas es de 50 Hz. Determine a cuáles de las siguientes frecuencias se les permite pasar y cuáles son rechazadas:

a) 1 Hz 

b) 20 Hz 

c) 50 Hz 

d) 60 Hz 

e) 30 kHz

14. ¿Cuál es fc para cada filtro de la figura 18-41? Determine el voltaje de salida a fc en cada caso (Vent = 10 V).

![image](https://user-images.githubusercontent.com/116771507/221471605-3550d6cb-2f2c-4ea7-b9ab-88c13f53f1f2.png)

16. Determine fc para cada una de las posiciones del interruptor en la figura 18-42.

![image](https://user-images.githubusercontent.com/116771507/221471637-9468d7ce-2803-4317-aadc-2d0c6d36a92c.png)

SECCIÓN 18–3 Filtros pasabanda

18. Suponiendo que la resistencia de devanado de las bobinas mostradas en la figura 18-43 es de 10 Ω, determine el ancho de banda para cada filtro.

![image](https://user-images.githubusercontent.com/116771507/221471683-b1c5d0de-c843-46b2-a46b-e8b0592d3638.png)

20. Para cada filtro mostrado en la figura 18-44, determine la frecuencia central de la pasabanda. Ignore RW

![image](https://user-images.githubusercontent.com/116771507/221471714-0e417e1d-1a24-4a74-b151-722ef0b245d1.png)

22. Determine la separación de las frecuencias centrales en todas las posiciones del interruptor de la figura 18-45. ¿Se traslapan algunas de las respuestas? Suponga que RW 5 = 0Ω para cada bobina.

![image](https://user-images.githubusercontent.com/116771507/221471780-3491136a-4984-45bf-94c5-7949e4678174.png)

SECCIÓN 18–4 Filtros Rechazabanda

24. Determine la frecuencia central para cada filtro mostrado en la figura 18-46.

![image](https://user-images.githubusercontent.com/116771507/221471828-6e9c691e-aec9-4bd5-83f4-59651906df5b.png)

26. Si la resistencia de las bobinas de la figura 18-47 es de 8 Ω, ¿cuál es el voltaje de salida en condición de resonancia cuando Vent = 50 V?

![image](https://user-images.githubusercontent.com/116771507/221471881-231a6a1a-e2ef-410b-bb66-cd328c8d5186.png)

4. VIDEO

5. CONCLUSIONES

6. BIBLIOGRAFÍA

FLOYD, THOMAS L. Principios de circuitos eléctricos. Octava edición. PEARSON EDUCACIÓN, México, 2007
































































