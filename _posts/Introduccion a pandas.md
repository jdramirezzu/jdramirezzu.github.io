---
layout: post
title: Introducción a pandas
---
**1.** Filtrar columnas: Se llama el indice y se especifica en una lista, las columnas que se quieren. 

		Df[['columna1', 'columna2']]
		
		
**2.** Filtrar con loc: Loc permite filtrar con la etiqueta de las columnas

		Df.loc[["indice_fila"], ["columna1", "columna2","etc"]]
		
**3.** Filtrar con iloc: se hace con los indices númericos


**4.** Establecer condiciones: 

			df[df['columna'] > 10]
			
					Ó
					
			df.query(condicion)
			
**5.** Eliminar duplicados 
```
            df.drop_duplicates()
```
