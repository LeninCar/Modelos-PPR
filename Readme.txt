README.txt

## Descripción general

Pasos necesarios para el proyecto en la interfaz.

1. Ejecución desde la interfaz web (IDE desplegable)

## Contenido de la carpeta

1. tests-parte1/
   Conjunto de datos de prueba (`.dzn`) para la Parte 1 del modelo.

2. tests-parte2/
   Conjunto de datos de prueba (`.dzn`) para la Parte 2 del modelo.

3. Informe.pdf
   Documento con la memoria, resultados y análisis del problema.

4. modelo_desenfreno_parte_1.mzn
   Modelo MiniZinc de la Parte 1 sin restricción de simetría.

5. modelo_desenfreno_parte_1-SIMETRIA.mzn
   Variante de la Parte 1 con restricción de simetría.

6. modelo_desenfreno_parte_2.mzn
   Modelo MiniZinc de la Parte 2 sin restricción de simetría.

7. modelo_desenfreno_parte_2-SIMETRIA.mzn
   Variante de la Parte 2 con restricción de simetría.

## Cómo ejecutar los modelos

### 1. Ejecución desde la interfaz web (Proyecto desplegado)

1. Acceder al enlace web proporcionado - https://proyecto-ppr-front-definitivo.vercel.app/
2. Allí ya estarán cargados los modelos (`.mzn`).
3. Selecciona la instancia que quieras ejecutar (parte 1 o parte 2).
4. Sube o selecciona el archivo `.dzn` correspondiente desde `tests-parte1/` o `tests-parte2/` u otros, pero se correspondientes a la parte del modelo a evaluar ya uqe las entradas para cada uno difieren.
5. Hacer clic en **Ejecutar** y espera los resultados.
6. Opcional: descarga el archivo de salida (`.txt`) con la solución.
