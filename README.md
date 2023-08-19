# Paralela_Lab1

## Instrucciones para compilar

piSeriesSeq.c
```bash
  gcc -o piSeriesSeq piSeriesSeq.c
```

piSeriesNaive.c
```bash
  gcc -o piSeriesNaive piSeriesNaive.c -fopenmp
```
El ejecutable recibe como parámetros la cantidad de iteraciones seguido de la cantidad de threads.

piSeriesNaive_copy.c
```bash
  gcc -o piSeriesNaiveCopy piSeriesNaive_copy.c -fopenmp
```
Los argumentos que recibe el ejecutable son el block size y la cantidad de threads.

piSeriesAlt.c
```bash
  gcc -o piSeriesAlt piSeriesAlt.c -fopenmp
```
El ejecutable recibe la cantidad de iteraciones y la cantidad de threads como argumentos de línea de comandos.
