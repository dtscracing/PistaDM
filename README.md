# Pista de slot plegable de dos tableros
 
Pista de slot casera pensada para montarse y empezar a jugar en **menos de 2 minutos**: dos tableros de **60 × 90 cm** que se ensamblan con tacos de madera, se alimentan al unirse y se guardan en poco espacio.

<img width="3072" height="3072" alt="IMG_20261010_110351" src="https://github.com/user-attachments/assets/3a4409d0-d399-4135-b02b-7931fff885c0" />

 
El repositorio incluye los dos SVG para corte láser y la guía de construcción.
 
## Contenido
 
| Archivo | Descripción |
|---|---|
| `tablero 1.svg` | Corte láser del tablero 1 (60 × 90 cm, DM de 5 mm) |
| `tablero 2.svg` | Corte láser del tablero 2 (60 × 90 cm, DM de 5 mm) |
 
 
## Cómo está hecha
 
Cada módulo es un sándwich de dos capas:
 
- **Capa superior (5 mm):** el diseño cortado con láser. Define el trazado, la ranura y la hendidura donde va el carril.
- **Base (5, 7 o 10 mm):** tablero liso del mismo tamaño que da rigidez y hace de fondo de la ranura.
La unión entre módulos es mecánica (tacos de madera) y eléctrica (dos conectores bala).
 
## Materiales
 
**Estructura**
- 2 tableros de 5 mm cortados con los SVG.
- 2 tableros base de 60 × 90 cm y 5, 7 o 10 mm.
- Cola de carpintero.
- Tacos o espigas de madera.
**Electricidad**
- Cinta de cobre autoadhesiva.
- 3 bananas hembra de panel para el mando (alimentación, salida a pista y freno).
- 1 conector de alimentación de panel para la fuente (yo usé un jack coaxial).
- 2 pares de **conectores bala** (*bullet connectors*, los de motor brushless a ESC), de 3,5 o 4 mm.
- Cable, estaño y fuente de alimentación adecuada para tus coches.
**Herramientas**
- Corte láser (propio o por encargo), taladro, soldador, sargentos o pesos para el encolado.
## Construcción
 
### 1. Corte
Corta los dos SVG en DM de 5 mm. Comprueba el escalado al importar el archivo: las piezas deben salir a 60 × 90 cm.
 
### 2. Encolado sobre la base
Pega cada tablero cortado sobre su base con cola de carpintero, extendida de forma uniforme y sin excesos que rebosen hacia la ranura. Alinea los cantos antes de apretar y prensa con sargentos o con peso repartido (yo usé libros) hasta que cure por completo. Yo dejé puesto el recorte sobrante de 4mm del carril para mantener la distancia del hueco, con cuidado de que no se pegue y se pueda retirar una vez seca la cola.   
 
### 3. Ensamblaje entre tableros
La unión es **machihembrada con tacos**:

<img width="3072" height="3072" alt="IMG_20261010_105644" src="https://github.com/user-attachments/assets/0eafc208-0b90-45a0-85a6-3ae14b9c8c61" />

 
1. En el canto de unión de un tablero, taladra los alojamientos y encola los tacos de forma que sobresalgan.
2. En el canto del otro tablero, taladra los agujeros correspondientes.
Marca la posición de los agujeros con los tableros juntos, o usa los tacos como plantilla, para que el encaje quede perfectamente alineado. Haz los agujeros con la misma broca que el diámetro del taco: el ajuste debe ser firme pero permitir separar los tableros sin esfuerzo. Comprueba que la junta queda a ras, porque un escalón en la ranura se nota con los coches. Tuve que retirar algo de material en los agujeros hasta conseguir que los tableros quedaran alineados en altura al montarlos.
 
### 4. Carriles
Aplica la **cinta de cobre autoadhesiva** siguiendo la hendidura del tablero.
 
- Limpia antes la superficie de polvo y restos de cola.
- Pega la cinta de forma continua, sin arrugas ni burbujas, y presiona bien con el dedo.
- Procura que los carriles queden bien cortados y aislados entre sí en el cruce de la junta.
- Si se rompe la cinta al colocarla se puede poner un punto de soldadura para asegurar el contacto.
### 5. Alimentación y mando
Monta los conectores en el **lateral** de uno de los tableros: el **conector de la fuente** (jack coaxial en mi caso) y **tres bananas** para el mando.
 
| Banana | Se conecta a | Función |
|---|---|---|
| **B1** | Negativo de la pista | Freno: al activarlo cortocircuita el motor del coche |
| **B2** | Positivo de la pista | Salida del mando hacia el carril |
| **B3** | Positivo de la fuente | Entrada de alimentación al mando |

<img width="3072" height="3072" alt="IMG_20261010_105750" src="https://github.com/user-attachments/assets/2c8fbee9-b961-44e8-9402-df95075ba6f1" />

 
El negativo de la fuente va directo al carril negativo. Suelda los cables a los carriles de cobre. Soldar directamente sobre la cinta funciona, pero hazlo rápido para no dañar el adhesivo, o suelda el cable a un extremo de la cinta antes de pegarla.
 
### 6. Paso de corriente entre tableros
La corriente pasa de un tablero al otro con **dos conectores bala**, uno por cada carril, fijados en los cantos que se unen. Macho en un tablero y hembra en el otro, de modo que se conecten solos al encajar.

<img width="1162" height="556" alt="Screenshot 14" src="https://github.com/user-attachments/assets/120ea421-7f2e-4abf-842e-d0834ce841fc" />
