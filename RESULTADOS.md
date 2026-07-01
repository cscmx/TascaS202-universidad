# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 15 correctas de 18 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.40 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.26 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.37 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.33 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.38 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,id_departamento

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.50 ms
✅ Se usó índice(s) en la consulta: PRIMARY,nif, PRIMARY, PRIMARY,id_asignatura,id_curso_escolar

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.51 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,id_departamento, id_profesor,id_grado

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,id_curso_escolar

---

## ✅ Query 10: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 11: Correcto

⏱ Tiempo: 0.30 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.28 ms
✅ Se usó índice(s) en la consulta: id_departamento

---

## ❌ Query 13: Incorrecto
```diff
--- 
+++ 
@@ -1,11 +1,63 @@
 apellido1 | apellido2 | nombre
-Schmidt | Fisher | David
-Kohler | Schoen | Alejandro
-Lemke | Rutherford | Cristina
-Fahey | Considine | Antonio
-Spencer | Lakin | Esther
-Streich | Hirthe | Carmen
-Ruecker | Upton | Guillermo
-Monahan | Murray | Micaela
-Stiedemann | Morissette | Alfredo
-Schowalter | Muller | Francesca
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
+NULL | NULL | NULL
```

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: PRIMARY, id_profesor

---

## ✅ Query 14: Correcto

⏱ Tiempo: 0.26 ms
✅ Se usó índice(s) en la consulta: id_profesor

---

## ❌ Query 15: Incorrecto
```diff
--- 
+++ 
@@ -1,10 +1,4 @@
 nombre
-Informática
-Matemáticas
-Economía y Empresa
-Educación
-Agronomía
-Química y Física
 Filología
 Derecho
 Biología y Geología
```

⏱ Tiempo: 0.29 ms
✅ Se usó índice(s) en la consulta: PRIMARY, id_departamento

---

## ✅ Query 16: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 17: Correcto

⏱ Tiempo: 0.26 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 18: Error
- **Descripción**: 'NoneType' object is not iterable

