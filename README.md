# Vision-Computador-VC-FIB
Encuentra las prácticas resueltas sobre la asignatura de Visión por Computador (VC) de la Facultad de Ingeniería Informática (FIB) de la Universidad Politécnica de Catalunya (UPC).

| Ejercicio | Nota  | Comentario  |
| :-------: | :---: | ------------------------------------------------------------------- |
| S1  | 10.0  | |
| E1  | 8.8 |     Poco rico en comentarios y la parte sobre la nube en 3D es muy "escueta"  |
| S2  | 10.0  | |
| E2  | 10.0  | |
| S3  | 10.0  | |
| E3  | 7.5 |     Utilizar doubles porque se redondean los valores y pierdes datos, no hacía falta binarizar los contronos con la función edge, la función de distancia al centro decae muy rápidamente en el centro, habría que ponderar los contornos con una única función gaussiana centrada a la imagen multiplicando las dos imagenes absSobel .* Gauss conseguimos hacer una ponderación sin usar bucles for. La sigma de la gaussiana habría que calcularla en función de los tamaños de la imagen. |
| S4  | 10.0  | |
| E4  | 9.3 |     No estaría de más que hubieráis probado alguna otra imagen. |
| E5  | 10.0  | |
| E6  | 7.0 | |
| E7  | 8.8 | |
| E8  | 9.0 | |
| Practica Checkpoint  |  9.0 |   Buen trabajo! Habría que dar más importancia a los falsos negativos, dado que podríamos descartarlos por tener un score bajo al usar la función predict. Esperaba que usárais otras features: Haar, LBP, Histogramas... |
| Practica Final  | 9.5 |        Buen trabajo! El video no muestra la detección de cejas, no costaría poner una indicación visual, igual que una línea con las posiciones encontradas... o la segmentación que ya figura en el documento. Creo que os quedáis con la primera ventana que detecta ojos y esta queda un poco demasiado arriba, habría que encontrar la mejor función score de la función predict. |
