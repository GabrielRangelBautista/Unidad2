# Unidad2
Unidada 2 de informatica de Gabriel Rangel

practica 2.1
BIT: Es la mínima pulsación electrónica que recibe una computadora (bit, binary digit: dígito binario); es decir, es la mínima cantidad de información (datos) que recibe una computadora y puede ser ya sea 0 o 1 y representa el estado de un dispositivo que puede tomar uno de dos estados. Un foco puede estar apagado o encendido.

BYTE Y UNIDADES DERIVADAS: Es la agrupación de 8 bits, un patrón con una longitud de 8 bits se llama byte. Este término también se ha utilizado para medir el tamaño de la memoria o de otros dispositivos de almacenamiento y se abrevia con la letra “B”.

En la siguiente tabla se mostraran el bit y sus multiplos los cuales nos facilitaran saber la cantidad de bytes contenidos en un archivo o dispositivo de almacenamiento, asi como tambien para cuantificar la capacidad de almacenamiento en la memoria principal.

<img src="https://github.com/GabrielRangelBautista/imagenes/blob/main/bit.png" alt="bytes" width="100%"/>

DATO: Se refiere a una representación simbólica o numérica de información. Los datos pueden ser cualquier tipo de información que se almacena y procesa en una computadora, como números texto, imágenes, sonidos, etc.

TIPOS DE DATOS: Audio, Imágen, Números, Texto, Video, etc.

DATO NUMÉRICO: Los programas utilizados en arquitectura o en ingeniería que procesa una computadora son de tipo numérico, aritmético, algebraico o trigonométrico; por ejemplo, es posible la resolución de raíces en una ecuación

DATO ALFANUMÉRICO (CARACTER O TEXTO): En este tipo de datos se utilizan programas de procesamiento de palabras o texto, que nos permiten corregir, borrar, justificar, mover, eliminar párrafos completos o sólo parte de ellos, corregir ortografía, etcétera

ARCHIVO: Un archivo, en informática, es una unidad de almacenamiento de datos que contiene información digital, como texto, imágenes, programas, documentos, hojas de cálculo, música, video, etc. Los archivos son utilizados para organizar y almacenar datos en dispositivos de almacenamiento, como discos duros, unidades flash, CD-ROM, DVD y otros medios de almacenamiento digital

SISTEMAS N8UMÉRICOS E INFORMACIÓN: El concepto de número y el proceso de desarrollo del conteo han sido históricamente registrados a lo largo del tiempo; sin embargo, sólo es posible identificar sus inicios por medio de amplias conjeturas.

SISTEMA DECIMAL: Este es el sistema numérico que usamos en la vida cotidiana. Está basado en la base 10, lo que significa que utiliza diez símbolos diferentes (0 al 9) para representar todos los números

SISTEMA BINARIO: El sistema binario se utiliza en informática y electrónica. Está basado en la base 2, lo que significa que utiliza solo dos símbolos (0 y 1) para representar números. Cada dígito en el sistema binario se llama "bit" (abreviatura de "binary digit")

SISTEMA HEXADECIMAL: El sistema hexadecimal está basado en la base 16 y utiliza los dígitos del 0 al 9 y las letras A a F para representar números. 

SISTEMA BASE-N: Además de los mencionados anteriormente, existen sistemas numéricos en base-n, donde "n" es cualquier número entero. Estos sistemas utilizan "n" símbolos diferentes para representar números

<img src="https://github.com/GabrielRangelBautista/imagenes/blob/main/mapa.png" alt="mapa" width="100%"/>

practica 2.2

Parte 1: Investigue los dos principales sistemas de codificación (ASCII, UTF-8 o Unicode) y haga una tabla comparativa en términos de ventajas y desventajas, métodos de conversión y aplicación de cada uno.

Ventajas y Desventajas

<img src="https://github.com/GabrielRangelBautista/imagenes/blob/main/BIT.jpg" alt="V y D" width="100%"/>

[![Alt text](https://img.youtube.com/vi/eaN2ZHTQZiL3uPic/0.jpg)](https://youtu.be/gfYx9JnAdNo?si=eaN2ZHTQZiL3uPic)

Parte 2: Identifique el código para cada carácter de su nombre y primer apellido y encuentre una función para generarlos utilizando ese código en LibreOffice portable (guía 1) y pruebe el siguiente convertidor Unicode online).

Identifique el codigo para cada caracter de su nombre y primer apellido

G A B R I E L 
U+0067 U+0061 U+0062 U+0072 U+0069 U+0065 U+006C

R A N G E L 
U+0072 U+0061 U+006E U+0067 U+0065 U+006C U+000A

Parte 3: Traduzca su nombre a tres tipos de caractares: Cirílico, Chino y Japonés e identyifique el código para cada símbolo y genere su nombre utilizando ese código en LibreOffice.
Español: 
Gabriel Rangel
U+0047 U+0061 U+0062 U+0072 U+0069 U+0065 U+006C U+0020 U+0052 U+0061 U+006E U+0067 U+0065 U+006C
cirilico:
Gabriel Rangel: Габриэль Рангель
U+0413 U+0430 U+0431 U+0440 U+0438 U+044D U+043B U+044C U+0020 U+0420 U+0430 U+043D U+0433 U+0435 U+043B U+044C
Chino:
Gabriel Rangel: 加布里埃爾·蘭格爾
U+52A0 U+5E03 U+91CC U+57C3 U+723E U+00B7 U+862D U+683C U+723E
Japones:
Gabriel Rangel: ガブリエル・ランゲル
U+30AC U+30D6 U+30EA U+30A8 U+30EB U+30FB U+30E9 U+30F3 U+30B2 U+30EB

| 😂 | 💀 | 😱 | 😎 | 😘 | 🍔 | ❤️ | ☢ | 🥰 | ✌ |
| :------------ |:---------------:| :---------------:| :-----:| :-----:| :-----:| :-----:| :-----:| :-----:| :-----:|
| U+1f602 | U+262x | U+1f631 | U+1f60e | U+1F618 | U+1f354 | U+2764 | U+2622 | U+262x | U+270c |

practica 2.3
[![Alt text](https://img.youtube.com/vi/SM5fkbLOeDe0AHx5/0.jpg)](https://youtu.be/PVMEKRpqXCA?si=SM5fkbLOeDe0AHx5)


practica 2.4

Número de lista: 16, correspondiente a los algoritmos 30 y 39

Algoritmo 30
Algoritmo par_impar
	
//DESCRIPCCION: Implementar un programa que sume todos los números pares entre 2 y n. El valor de n se medirá al principio.
definir n Como Entero;
	Escribir "Por favor ingrese un número";
	
	//INICIO
	Leer n;
	
	Para i= 2 Hasta n Hacer;
		
		Si i%2=0 Entonces
			suma = suma +1;
		Fin Si
		
	Fin Para

	Escribir "La suma es" suma;
	
FinAlgoritmo
<img src="https://github.com/GabrielRangelBautista/imagenes/blob/main/30.png" alt="30" width="100%"/>

Algoritmo 39
ALGORITMO Reprobados
//DESCRICCION: Leer 50 calificaciones de un grupo de alumnos. Calcule y escriba el porcentaje de reprobados. Tomando en cuenta que la calificaron mínima aprobatoria es de 70 
	Definir i Como Entero;
	definir calf Como Real;
	
	p= 0;
			
	//INICIO
	
	Para i<-1 Hasta i= 50 Hacer;
		Leer calf;
		Si (calf<7.0 y cal>0) Entonces
			p= p+1;
		SiNo 
			Escribir "No esta reprobado";
		Fin Si
		
	Fin Para
	
	Escribir "Porcentaje de reprobados" p*100/50;;
			
				
			
FinAlgoritmo
<img src="https://github.com/GabrielRangelBautista/imagenes/blob/main/39.png" alt="39" width="100%"/>

practica 2.5

[![Alt text](https://img.youtube.com/vi/oKzxlX33-aUIUwnO/0.jpg)](https://youtu.be/HhEyT7De4Ak?si=oKzxlX33-aUIUwnO)

