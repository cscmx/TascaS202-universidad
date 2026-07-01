# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 16 correctas de 21 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.40 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.31 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.37 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_departamento, PRIMARY

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.50 ms
✅ Se usó índice(s) en la consulta: PRIMARY,nif, PRIMARY,id_asignatura,id_curso_escolar, PRIMARY

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.56 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_departamento, id_profesor,id_grado, PRIMARY

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_curso_escolar, PRIMARY

---

## ✅ Query 10: Correcto

⏱ Tiempo: 0.38 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 11: Correcto

⏱ Tiempo: 0.32 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.29 ms
✅ Se usó índice(s) en la consulta: id_departamento

---

## ❌ Query 13: Incorrecto
```diff
--- 
+++ 
@@ -1,11 +1,11 @@
 apellido1 | apellido2 | nombre
 Schmidt | Fisher | David
-Kohler | Schoen | Alejandro
 Lemke | Rutherford | Cristina
-Fahey | Considine | Antonio
 Spencer | Lakin | Esther
 Streich | Hirthe | Carmen
+Stiedemann | Morissette | Alfredo
+Kohler | Schoen | Alejandro
+Fahey | Considine | Antonio
 Ruecker | Upton | Guillermo
 Monahan | Murray | Micaela
-Stiedemann | Morissette | Alfredo
 Schowalter | Muller | Francesca
```

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: id_profesor, PRIMARY

---

## ✅ Query 14: Correcto

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: id_profesor

---

## ❌ Query 15: Incorrecto
```diff
--- 
+++ 
@@ -1,5 +1,4 @@
 nombre
-Informática
 Matemáticas
 Economía y Empresa
 Educación
```

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: id_profesor, id_departamento

---

## ✅ Query 16: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 17: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 18: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: id_departamento, PRIMARY

---

## ❌ Query 19: Incorrecto
```diff
--- 
+++ 
@@ -1,10 +1,13 @@
-departamento | total
-Informática | 2.00
-Matemáticas | 2.00
-Economía y Empresa | 2.00
-Educación | 3.00
-Agronomía | 1.00
-Química y Física | 2.00
-Filología | 0.00
-Derecho | 0.00
-Biología y Geología | 0.00
+nombre | nombre
+Informática | Zoe
+Informática | Manolo
+Matemáticas | David
+Matemáticas | Alejandro
+Economía y Empresa | Cristina
+Economía y Empresa | Antonio
+Educación | Esther
+Educación | Carmen
+Educación | Guillermo
+Agronomía | Micaela
+Química y Física | Alfredo
+Química y Física | Francesca
```

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_departamento, PRIMARY

---

## ❌ Query 20: Incorrecto
```diff
--- 
+++ 
@@ -1,11 +1,84 @@
 grau | total
-Grado en Ingeniería Informática (Plan 2015) | 51.00
-Grado en Biotecnología (Plan 2015) | 32.00
-Grado en Ingeniería Agrícola (Plan 2015) | 0.00
-Grado en Ingeniería Eléctrica (Plan 2014) | 0.00
-Grado en Ingeniería Electrónica Industrial (Plan 2010) | 0.00
-Grado en Ingeniería Mecánica (Plan 2010) | 0.00
-Grado en Ingeniería Química Industrial (Plan 2010) | 0.00
-Grado en Ciencias Ambientales (Plan 2009) | 0.00
-Grado en Matemáticas (Plan 2010) | 0.00
-Grado en Química (Plan 2009) | 0.00
+Grado en Biotecnología (Plan 2015) | Virología
+Grado en Ingeniería Informática (Plan 2015) | Tratamiento digital de imágenes
+Grado en Biotecnología (Plan 2015) | Termodinámica y cinética química aplicada
+Grado en Ingeniería Informática (Plan 2015) | Teoría de códigos y criptografía
+Grado en Ingeniería Informática (Plan 2015) | Tecnologías web
+Grado en Ingeniería Informática (Plan 2015) | Tecnologías multimedia
+Grado en Ingeniería Informática (Plan 2015) | Tecnologías de acceso a red
+Grado en Biotecnología (Plan 2015) | Técnicas instrumentales básicas
+Grado en Biotecnología (Plan 2015) | Técnicas instrumentales avanzadas
+Grado en Ingeniería Informática (Plan 2015) | Sistemas Operativos
+Grado en Ingeniería Informática (Plan 2015) | Sistemas Inteligentes
+Grado en Ingeniería Informática (Plan 2015) | Sistemas de tiempo real
+Grado en Ingeniería Informática (Plan 2015) | Sistema de Información para las Organizaciones
+Grado en Ingeniería Informática (Plan 2015) | Seguridad y cumplimiento normativo
+Grado en Ingeniería Informática (Plan 2015) | Seguridad Informática
+Grado en Biotecnología (Plan 2015) | Química orgánica
+Grado en Biotecnología (Plan 2015) | Química general
+Grado en Ingeniería Informática (Plan 2015) | Programación de Servicios Software
+Grado en Ingeniería Informática (Plan 2015) | Procesos de Ingeniería del Software 2
+Grado en Ingeniería Informática (Plan 2015) | Procesos de Ingeniería del Software 1
+Grado en Biotecnología (Plan 2015) | Procesos biotecnológicos
+Grado en Ingeniería Informática (Plan 2015) | Planificación y Gestión de Proyectos Informáticos
+Grado en Ingeniería Informática (Plan 2015) | Periféricos e interfaces
+Grado en Biotecnología (Plan 2015) | Patología molecular de plantas
+Grado en Ingeniería Informática (Plan 2015) | Organización y gestión de empresas
+Grado en Biotecnología (Plan 2015) | Operaciones de separación
+Grado en Ingeniería Informática (Plan 2015) | Negocio Electrónico
+Grado en Ingeniería Informática (Plan 2015) | Multiprocesadores
+Grado en Ingeniería Informática (Plan 2015) | Modelado y Diseño del Software 2
+Grado en Ingeniería Informática (Plan 2015) | Modelado y Diseño del Software 1
+Grado en Biotecnología (Plan 2015) | Microbiología
+Grado en Ingeniería Informática (Plan 2015) | Metodología de la programación
+Grado en Biotecnología (Plan 2015) | Metabolismo y biosíntesis de biomoléculas
+Grado en Biotecnología (Plan 2015) | Matemáticas II
+Grado en Biotecnología (Plan 2015) | Matemáticas I
+Grado en Ingeniería Informática (Plan 2015) | Lógica y algorítmica
+Grado en Ingeniería Informática (Plan 2015) | Líneas de Productos Software
+Grado en Ingeniería Informática (Plan 2015) | Introducción a la programación
+Grado en Ingeniería Informática (Plan 2015) | Inteligencia del Negocio
+Grado en Ingeniería Informática (Plan 2015) | Integración de las Tecnologías de la Información en las Organizaciones
+Grado en Biotecnología (Plan 2015) | Inmunología
+Grado en Biotecnología (Plan 2015) | Ingeniería genética
+Grado en Ingeniería Informática (Plan 2015) | Ingeniería del Software
+Grado en Ingeniería Informática (Plan 2015) | Ingeniería de Sistemas de Información
+Grado en Ingeniería Informática (Plan 2015) | Ingeniería de Requisitos
+Grado en Biotecnología (Plan 2015) | Ingeniería bioquímica
+Grado en Ingeniería Informática (Plan 2015) | Informática industrial y robótica
+Grado en Ingeniería Informática (Plan 2015) | Herramientas y Métodos de Ingeniería del Software
+Grado en Ingeniería Informática (Plan 2015) | Gestión de la Calidad y de la Innovación Tecnológica
+Grado en Biotecnología (Plan 2015) | Genómica y proteómica
+Grado en Biotecnología (Plan 2015) | Genética molecular
+Grado en Biotecnología (Plan 2015) | Genética
+Grado en Ingeniería Informática (Plan 2015) | Fundamentos de Redes de Computadores
+Grado en Ingeniería Informática (Plan 2015) | Fundamentos de electrónica
+Grado en Biotecnología (Plan 2015) | Fisiología vegetal
+Grado en Biotecnología (Plan 2015) | Fisiología animal
+Grado en Ingeniería Informática (Plan 2015) | Física para informática
+Grado en Biotecnología (Plan 2015) | Física
+Grado en Ingeniería Informática (Plan 2015) | Fiabilidad y Gestión de Riesgos
+Grado en Ingeniería Informática (Plan 2015) | Estructura y tecnología de computadores
+Grado en Ingeniería Informática (Plan 2015) | Estructura de Datos y Algoritmos II
+Grado en Ingeniería Informática (Plan 2015) | Estructura de Datos y Algoritmos I
+Grado en Ingeniería Informática (Plan 2015) | Estadística
+Grado en Ingeniería Informática (Plan 2015) | Desarrollo Rápido de Aplicaciones
+Grado en Ingeniería Informática (Plan 2015) | Desarrollo de interfaces de usuario
+Grado en Ingeniería Informática (Plan 2015) | Cálculo
+Grado en Biotecnología (Plan 2015) | Botánica agrícola
+Grado en Biotecnología (Plan 2015) | Biotecnología vegetal
+Grado en Biotecnología (Plan 2015) | Biotecnología microbiana
+Grado en Biotecnología (Plan 2015) | Biotecnología de los productos hortofrutículas
+Grado en Biotecnología (Plan 2015) | Biorreactores
+Grado en Biotecnología (Plan 2015) | Bioquímica
+Grado en Biotecnología (Plan 2015) | Biología vegetal y animal
+Grado en Biotecnología (Plan 2015) | Biologia celular
+Grado en Biotecnología (Plan 2015) | Bioinformática
+Grado en Biotecnología (Plan 2015) | Bases moleculares del desarrollo vegetal
+Grado en Ingeniería Informática (Plan 2015) | Bases de Datos
+Grado en Ingeniería Informática (Plan 2015) | Arquitectura de Computadores
+Grado en Ingeniería Informática (Plan 2015) | Análisis y planificación de las TI
+Grado en Ingeniería Informática (Plan 2015) | Almacenes de Datos
+Grado en Ingeniería Informática (Plan 2015) | Álgegra lineal y matemática discreta
+Grado en Ingeniería Informática (Plan 2015) | Administración de redes y sistemas operativos
+Grado en Ingeniería Informática (Plan 2015) | Administración de bases de datos
```

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: id_grado, PRIMARY

---

## ❌ Query 21: Error
- **Descripción**: 'NoneType' object is not iterable

