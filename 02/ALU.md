### DESCRIPCIÓN DE LA ALU
## Modelo de Von Neumann

En computación, la unidad aritmética lógica o unidad aritmético-lógica, también conocida como ALU (siglas en inglés de arithmetic logic unit), es un circuito digital que calcula operaciones aritméticas (como suma, resta, multiplicación, etc.) y operaciones lógicas (si, y, o, no), entre valores (generalmente uno o dos) de los argumentos.

Por mucho, los circuitos electrónicos más complejos son los que están construidos dentro de los chips de microprocesadores modernos. Por lo tanto, estos procesadores tienen dentro de ellos un ALU muy complejo y potente. De hecho, un microprocesador moderno (y los mainframes) puede tener múltiples núcleos, cada núcleo con múltiples unidades de ejecución, cada una de ellas con múltiples ALU.

Von Neumann explicó que una ALU es un requisito fundamental para una computadora porque necesita efectuar operaciones matemáticas básicas: adición, sustracción, multiplicación, y división.1​ Por lo tanto, creyó que era "razonable que una computadora debería contener los órganos especializados para estas operaciones".1​

### Esquema de una ALU

![ALU NAND2TETRIS](http://serbal.pntic.mec.es/irec0010/imagenes/alu.gif "alu")

### Elementos de la ALU
* **Operador** Circuitos electrónicos combinacionales que relizaban una función aritmética
* **Banco de Registros**: (de tipo general) donde almacena los datos
* **Un Registro Acumulador**: Se deposita el resultado de la operación.
* **Señalizadores: Biestables**: Señalizan ciertas condiciones de la última operación. Por ejemplo, overflow (se realiza una operación y el resultado es tan grande que no cabe en el acumulador) el señalizador de overflow aparecerá un 1 que informa del error.

![ALU ELMENTOS](./images/picture3.png?raw=true "ELEMENTOS DE LA ALU")

## Ejemplo de ALU de Nand2Tetris

![ALU NAND2TETRIS](./images/alu.jpg?raw=true "ALU NAN2TETRIS")

### Detalles de diseño de nuestra ALU

![ALU tech NAND2TETRIS](./images/ALU_SPECIFICATION.jpg?raw=true "ALU_SPECIFICATION NAN2TETRIS") 

### IMPLEMENTACIONES DE LA ALU EN NAND2TETRIS
![ALU IMP1](./images/picture1.png?raw=true "implementación modelo 1")

![ALU IMP2](./images/picture2.png?raw=true "implementación modelo 2")


REFERENCES
---
https://www.slideshare.net/youtang5/introduction-to-nand2-tetris Curso básico de Nand2Tetris
