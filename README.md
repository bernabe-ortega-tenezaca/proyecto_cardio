# Pipeline de Análisis — Heart Disease Dataset

Análisis exploratorio del dataset cardiovascular de la UCI.
El pipeline carga, limpia y analiza 303 registros clínicos
para explorar patrones asociados a enfermedades cardíacas.

## Autor
[Bernabe Ortega-Tenezaca]
Instituto de Analítica y Negocios — Lima, Perú
Curso 1: Git & GitHub para Data Science

## Instalación
pip install ucimlrepo pandas matplotlib seaborn

## Ejecución
Abrir y ejecutar el notebook main.ipynb en orden.

## Estructura del proyecto
    data/ Datos generados por el notebook (ignorados por Git)
    outputs/ Figuras y resúmenes generados (ignorados por Git)
    main.ipynb Notebook principal del pipeline
    README.md Descripción del proyecto
    .gitignore Archivos excluidos del control de versiones

7ff596d (HEAD -> main) feat: analisis exploratorio con tres visualizaciones
7b6cd46 feat: limpieza de valores invalidos y duplicados
5c0fb73 feat: inspeccion inicial del dataset
1d66252 feat: cargar dataset cardiovascular desde UCI
bc83b31 chore: agregar notebook principal del pipeline
9976007 chore: inicializar estructura del proyecto

## Resultado clave
El 45.9% de los pacientes del dataset presenta enfermedad cardíaca.

## Decisiones del historial
En la Fase 2 se usó ‘git reset HEAD~1‘ para deshacer un commit
cuyo mensaje no era descriptivo ("cambios"). Los archivos
modificados se conservaron y se volvieron a commitear con
un mensaje que explica claramente qué cambió y por qué.
Esta práctica es útil antes de hacer push al remoto, cuando
aún es posible reescribir el historial local sin afectar
a otros colaboradores.

- Rama estadisticas: resumen por grupo de edad agregado.