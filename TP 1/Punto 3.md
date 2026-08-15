# Modulación BPSK y Tasa de Error de Bit (BER)

1. La señal está modulada en **BPSK** o Modulación por desplazamiento de Fase.

2. Siguiendo la modulación en BPSK, tendríamos:

   ![Diagrama de modulación BPSK](diagrama_bpsk.png)

3. Además de PSK, también tenemos:

   * Modulación por desplazamiento de frecuencia (FSK)
   * Modulación por desplazamiento de amplitud (ASK)

4. El Bit Error Rate (BER) es la medida más habitual para determinar la cantidad de errores en cualquier línea de transmisión de datos; se define como la probabilidad de que un bit se reciba erróneamente. También se denomina fracción de errores por bit. Este último término es más esclarecedor, ya que el término tasa se refiere normalmente a una cantidad que varía con el tiempo. Desgraciadamente, la mayoría de los libros y documentos de normalización consideran a la R de BER cómo Rate (tasa) y no como Ratio (fracción).

   1. En cuanto a las prestaciones, la modulación por desplazamiento de fase (PSK) es la mejor y se consigue una mayor eficiencia si se utiliza una señalización multinivel. Por otro lado, ASK y FSK proporcionan la misma eficiencia del ancho de banda.
