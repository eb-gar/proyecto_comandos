# 📘 Informe - Práctica No. 1

## 🛠 Desarrollo de la práctica

### 1. Creación de estructura de carpetas

```bash
mkdir proyecto_comandos
cd proyecto_comandos
mkdir documentos imagenes scripts
```

### 2. Manipulación de archivos

* Crear `notas.txt` en documentos:

```bash
echo "Primera nota" > notas.txt
echo "Segunda nota" >> notas.txt
echo "Tercera nota" >> notas.txt
```

* Copiar y mover archivos:

```bash
cp notas.txt ../scripts/backup_notas.txt
mv backup_notas.txt ../imagenes/
```

### 3. Redirección y concatenación

```bash
cat notas.txt > resumen.txt
echo "Nueva línea agregada" >> resumen.txt
```

### 4. Eliminación de archivos y carpetas

```bash
rm backup_notas.txt
rm -r imagenes
```

### 5. Guardar historial en archivo

```bash
history > tarea-s1-nombre_apellido.txt
```

---

## 📂 Archivos generados

* `notas.txt`
* `resumen.txt`
* `tarea-s1-Estrella_Garcia.txt`

---

## 🎤 Evidencia adicional

* Se adjunta un carpeta con imagenes con un resumen de lo aprendido.