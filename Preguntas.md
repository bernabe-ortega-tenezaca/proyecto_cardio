Preguntas Conceptuales

Marca con una X la única respuesta correcta.
Pregunta 1. ¿Qué ocurre exactamente cuando ejecutas git add sobre un archivo?
a) El archivo se guarda en el repositorio con un nuevo commit.
b) El archivo se copia al Staging Area, listo para el próximo commit.
c) El archivo se sube automáticamente al repositorio remoto.
d) Git crea una nueva rama con los cambios del archivo.
Respuesta: b

Pregunta 2. Usaste git reset HEAD~1 para deshacer un commit. ¿Cuál es la diferencia
principal respecto a git reset –hard HEAD~1?
a) Ambos comandos hacen exactamente lo mismo.
b) Con HEAD~1 se borra el commit pero los cambios en los archivos se conservan; con
–hard se borra el commit Y los cambios también.
c) Con –hard se crea una nueva rama; con HEAD~1 no.
d) HEAD~1 borra el commit y –hard solo cambia el mensaje del commit.
Respuesta: b

Pregunta 3. En la Fase 3, al fusionar las dos ramas a main, Git generó un conflicto en
README.md. ¿Por qué ocurrió ese conflicto?
a) Porque main.ipynb es un archivo binario que Git ignora siempre.
b) Porque ambas ramas modificaron la misma zona del README.md y Git no puede
decidir solo cuál versión conservar.
c) Porque README.md no estaba incluido en el .gitignore.
d) Porque Git solo genera conflictos en archivos de texto plano.
Respuesta: b

Pregunta 4. ¿Qué muestra el flag –graph al ejecutar git log –oneline –graph?
a) Un diagrama de los archivos modificados en cada commit.
b) La representación visual de cómo se bifurcan y convergen las ramas en el historial
de commits.
c) La lista de colaboradores que participaron en cada commit.
d) El diff de los cambios introducidos en cada commit.
Respuesta: b

Pregunta 5. Un compañero revisa tu proyecto tres semanas después y ve este commit
en el historial: "feat: limpieza de valores invalidos y duplicados". ¿Qué ventaja
concreta le da ese mensaje frente a uno como çambios"?
a) Ninguna. El mensaje de commit no afecta el funcionamiento del código.
b) Le permite saber qué tipo de transformación se hizo y en qué parte del pipeline, sin
necesidad de abrir el archivo ni el diff.
c) Le permite revertir el commit más rápido usando git revert.
d) Le indica en qué rama se hizo el commit originalmente.
Respuesta: b