# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 6 correctas de 11 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.46 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.31 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.31 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.32 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ❌ Query 6: Incorrecto
```diff
--- 
+++ 
@@ -1,13 +1,13 @@
 apellido1 | apellido2 | nombre | departamento
-Fahey | Considine | Antonio | Economía y Empresa
+Ramirez | Gea | Zoe | Informática
 Hamill | Kozey | Manolo | Informática
+Schmidt | Fisher | David | Matemáticas
 Kohler | Schoen | Alejandro | Matemáticas
 Lemke | Rutherford | Cristina | Economía y Empresa
+Fahey | Considine | Antonio | Economía y Empresa
+Spencer | Lakin | Esther | Educación
+Streich | Hirthe | Carmen | Educación
+Ruecker | Upton | Guillermo | Educación
 Monahan | Murray | Micaela | Agronomía
-Ramirez | Gea | Zoe | Informática
-Ruecker | Upton | Guillermo | Educación
-Schmidt | Fisher | David | Matemáticas
+Stiedemann | Morissette | Alfredo | Química y Física
 Schowalter | Muller | Francesca | Química y Física
-Spencer | Lakin | Esther | Educación
-Stiedemann | Morissette | Alfredo | Química y Física
-Streich | Hirthe | Carmen | Educación
```

⏱ Tiempo: 0.37 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,id_departamento

---

## ❌ Query 7: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,16 @@
 nombre | anyo_inicio | anyo_fin
 Álgegra lineal y matemática discreta | 2014.00 | 2015.00
-Cálculo | 2014.00 | 2015.00
-Física para informática | 2014.00 | 2015.00
+Álgegra lineal y matemática discreta | 2014.00 | 2015.00
+Álgegra lineal y matemática discreta | 2014.00 | 2015.00
+Álgegra lineal y matemática discreta | 2015.00 | 2016.00
+Álgegra lineal y matemática discreta | 2015.00 | 2016.00
+Álgegra lineal y matemática discreta | 2015.00 | 2016.00
+Álgegra lineal y matemática discreta | 2016.00 | 2017.00
+Álgegra lineal y matemática discreta | 2016.00 | 2017.00
+Álgegra lineal y matemática discreta | 2016.00 | 2017.00
+Álgegra lineal y matemática discreta | 2017.00 | 2018.00
+Álgegra lineal y matemática discreta | 2017.00 | 2018.00
+Álgegra lineal y matemática discreta | 2017.00 | 2018.00
+Álgegra lineal y matemática discreta | 2018.00 | 2019.00
+Álgegra lineal y matemática discreta | 2018.00 | 2019.00
+Álgegra lineal y matemática discreta | 2018.00 | 2019.00
```

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,nif

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.50 ms
✅ Se usó índice(s) en la consulta: id_profesor,id_grado, PRIMARY, PRIMARY,id_departamento

---

## ❌ Query 9: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1 @@
 nombre | apellido1 | apellido2
-Inma | Lakin | Yundt
-Irene | Hernández | Martínez
-Sonia | Gea | Ruiz
```

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ❌ Query 10: Incorrecto
```diff
--- 
+++ 
@@ -1,13 +1,13 @@
 departamento | apellido1 | apellido2 | nombre
 Agronomía | Monahan | Murray | Micaela
+Economía y Empresa | Lemke | Rutherford | Cristina
 Economía y Empresa | Fahey | Considine | Antonio
-Economía y Empresa | Lemke | Rutherford | Cristina
-Educación | Ruecker | Upton | Guillermo
 Educación | Spencer | Lakin | Esther
 Educación | Streich | Hirthe | Carmen
+Educación | Ruecker | Upton | Guillermo
+Informática | Ramirez | Gea | Zoe
 Informática | Hamill | Kozey | Manolo
-Informática | Ramirez | Gea | Zoe
+Matemáticas | Schmidt | Fisher | David
 Matemáticas | Kohler | Schoen | Alejandro
-Matemáticas | Schmidt | Fisher | David
+Química y Física | Stiedemann | Morissette | Alfredo
 Química y Física | Schowalter | Muller | Francesca
-Química y Física | Stiedemann | Morissette | Alfredo
```

⏱ Tiempo: 0.39 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ❌ Query 11: Error
- **Descripción**: 'NoneType' object is not iterable

