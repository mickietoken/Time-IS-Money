<div align="center">

# PROYECTO El Tiempo ES Dinero

Una iniciativa de programación para construir un programa experimental con un algoritmo único llamado AVC (Automatización/Valoración/Moneda).

---
</div>

## LA IDEA

La idea es crear un activo que demuestre exactamente dónde alcanzará su punto máximo, cuándo se desplomará y cuántas veces alcanzará su máximo histórico para que los inversores sepan exactamente cuándo invertir, cuánto tiempo mantenerlo y cuándo vender con un riesgo mínimo. Utilizando un algoritmo que valora automáticamente dicho activo usando el tiempo para aumentar su valor en incrementos con bitcoin como moneda de referencia.

Actualmente, cada activo del mundo que se puede comerciar se valora ya sea por sentimiento o por condiciones de mercado. Donde observamos gráficos y esperamos lo mejor todo el día.

Con el AVC, el activo (Tokenmobiles) será AUTOEVALUADO... algo que nunca ha existido antes.

Para que esto se lleve a cabo, se necesitan programadores experimentados para construir su propia versión del programa. (Se necesitan al menos 100 versiones para un lanzamiento seguro y sostenible).

Una vez iniciado en el DÍA DE IGNICIÓN, el programa debe ejecutarse sin interrupción durante más de 200 años y NUNCA PUEDE SER DETENIDO.

El programa debe ser como el tiempo mundial en sí mismo, múltiples versiones ejecutándose en varios servidores, varios dispositivos, todos siguiendo el mismo patrón/algoritmo.

Antes de que los programadores comiencen a construir su versión del programa con las herramientas de su elección, necesitarán conocer las características/detalles fundamentales del activo y del algoritmo AVC.

-
-
-
-

## EL ACTIVO

Se desplegaron 100 contratos inteligentes estándar de tokens fungibles en la blockchain de Stacks.

Cada contrato inteligente tiene 1 Tokenmobile único con un suministro que varía entre 200 y 50,000.

En total, hay 999,999 Tokenmobiles.

Cada Tokenmobile único tiene atributos/metadatos esenciales para el algoritmo AVC.

![](/media/asset.png)

**TIPO** - La etiqueta/nombre del Tokenmobile en código morse.

**SUMINISTRO** - 1 token de la cantidad fija en el contrato inteligente.

**CICLOS** - La cantidad de veces que el Tokenmobile colapsará/reiniciará su valor y se recuperará nuevamente.

**IMPULSO** - El porcentaje de aumento en la duración del ciclo del Tokenmobile cada vez que se reinicia, incrementando así su valor máximo.

**INICIO** - La duración del primer ciclo.

**MÁXIMO** - La duración del último ciclo.

**AVC** - El algoritmo/motor que valora cada Tokenmobile.

-
-
-
-

## EL ALGORITMO

• A de **Automatización**. La automatización siendo el **TIEMPO**, y el tiempo siendo **60 segundos**.  

• V de **Valoración**. La valoración siendo en incrementos de **0.00001 o 0.00003**.  

• C de **Moneda**. La moneda siendo **₿itcoin**, utilizada como referencia para valorar los Tokenmobiles.  

Por lo tanto, un Tokenmobile aumentará **₿0.00001 o ₿0.00003 cada 60 segundos**.

-
-
-
-

## EL PROGRAMA

![](/media/program.jpg)

Aquí hay una demostración del programa ejecutando el algoritmo AVC.  
[VER DEMO](https://drive.google.com/file/d/10M1PcLHT_r6kEz8bumL3yzdjFDoLvsWI/view?usp=drivesdk)

Estás viendo 2 **RACKS** de 2 Tokenmobiles siendo valorados por el AVC. (El programa oficial tendrá 100 RACKS).

1. Es la dirección del contrato inteligente / ubicación del activo que está siendo valorado.

2. Es la cuenta regresiva en vivo, formateada en **AA/DDD/HH/MM/SS** (Nota: los DÍAS son de 365. Sin años bisiestos, sin semanas, sin meses, sin milisegundos).

3. Es la marca de tiempo de cuándo terminará el ciclo actual / cuándo la cuenta regresiva se detendrá para reiniciarse. (Las marcas de tiempo de cada ciclo de cada Tokenmobile están en el archivo FUNDAMENTOS).

4. Es el total de **CICLOS**, que disminuye cada vez que la cuenta regresiva se reinicia y la marca de tiempo se actualiza.  
   *(Nota: el primer ciclo debe disminuir inmediatamente cuando el AVC de un Tokenmobile comienza, y no después de que termine).*

5. Es el **IMPULSO**.  
6. Es el **SUMINISTRO**.  

*(Impulso y suministro solo son para mostrar en la interfaz de usuario. No tienen ninguna función en el código.)*

7. Es el **AVC/Valor** del Tokenmobile, el cual aumentará en **₿0.00001 o ₿0.00003** cada vez que la cuenta regresiva alcance 60 segundos.  
   El valor se reinicia a **₿0.00000** cuando comienza un nuevo ciclo. *(Nota: al final del ciclo final, el valor debe detenerse y permanecer en su máxima valoración.)*

El programa oficial listo para el **DÍA DE IGNICIÓN** debe tener **100 RACKS** de cada uno de los **100 contratos inteligentes de Tokenmobiles**, todos iniciados juntos y ejecutándose en **AVC simultáneamente** hasta que cada uno complete su ciclo de valoración.

El **Tokenmobiles-100** será el primero en terminar, después de solo **60 días**, con una valoración máxima de **₿0.86400**, y el **Tokenmobiles-43** será el último en terminar, después de más de **200 años**, con una valoración máxima de **₿338.93753**.

El programa también requiere una **infraestructura de backend**, una **interfaz frontend** para mostrar actualizaciones en tiempo real **sin retraso**, y una solución de **hosting capaz de garantizar un 99.99% de tiempo de actividad por más de 200 años**.

-
-
-
-

## EL CÓDIGO

No existe una plantilla o código abierto para el programa/AVC desde el cual comenzar. Y la demostración fue programada solo para ejecutarse en la terminal como demostración visual.

Se espera que cada programador **desarrolle su propia versión del programa desde cero**, utilizando sus herramientas de preferencia, su propio servidor, solución de hosting y los **fundamentos proporcionados**.

La razón de esto es para **evitar versiones duplicadas con los mismos posibles errores en el código**. Debe haber **diferentes implementaciones del mismo programa**, asegurando así la **longevidad y seguridad** del sistema.

-
-
-
-

## EL ENTORNO

La iniciativa **Time IS Money** estará activa en **GitHub y Discord**, donde los programadores podrán unirse para discutir y actualizar su progreso en el desarrollo del programa.

Una vez que los programadores hayan construido y compartido **pruebas de ejecución del programa**, recibirán la fecha del **DÍA DE IGNICIÓN** para ejecutar oficialmente el programa en vivo, junto con un paquete del activo que el programa valora. *(10 años del primer ciclo en Tokenmobiles).*

-
-
-
-

## EL LOGRO

Si más de **100 versiones** del programa se ejecutan en vivo en el **DÍA DE IGNICIÓN**, ya sea de manera pública o privada, el **activo y el programa** habrán asegurado **significancia e importancia** instantáneamente.

Comparado con **acciones, metales, criptomonedas, ETFs, etc.**, sería **el único activo autoevaluado en el mundo**.
