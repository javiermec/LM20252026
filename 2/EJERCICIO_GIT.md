Genial, te diseño un **ejercicio de introducción a Git** para primer día de clase, pensado para que el alumnado lo haga paso a paso y vea resultados inmediatos. Lo planteo en modo “guía práctica” con comandos listos para usar.

---

# 📝 **Ejercicio: Mi primer repositorio con Git**

📌 **Objetivo:** aprender a crear un repositorio local, registrar cambios y consultar el historial con Git.

---

## **Parte 1. Preparar el entorno**

1. Abrir **VS Code** (o un terminal con Git Bash).
2. Crear una carpeta para el ejercicio:

   ```bash
   mkdir mi_primer_repo
   cd mi_primer_repo
   ```
3. Inicializar Git en la carpeta:

   ```bash
   git init
   ```

   👉 Esto crea la carpeta oculta `.git` (el “cerebro” del repositorio).

---

## **Parte 2. Crear el primer archivo**

1. Crear un archivo `index.html` con el siguiente contenido:

   ```html
   <h1>Hola Mundo</h1>
   ```
2. Guardar el archivo.
3. Verificar el estado del repositorio:

   ```bash
   git status
   ```

   👉 Git dirá que hay un archivo nuevo sin seguimiento (`Untracked file`).

---

## **Parte 3. Primer commit**

1. Añadir el archivo al área de preparación:

   ```bash
   git add index.html
   ```
2. Confirmar el cambio con un mensaje:

   ```bash
   git commit -m "Primer commit: archivo inicial con Hola Mundo"
   ```
3. Revisar el historial:

   ```bash
   git log --oneline
   ```

---

## **Parte 4. Segundo commit**

1. Editar `index.html` y añadir una línea:

   ```html
   <p>Bienvenidos a la clase de Git</p>
   ```
2. Guardar el archivo.
3. Ver los cambios pendientes:

   ```bash
   git diff
   ```
4. Añadir y confirmar:

   ```bash
   git add index.html
   git commit -m "Segundo commit: añadido párrafo de bienvenida"
   ```

---

## **Parte 5. Explorar el historial**

1. Ver commits resumidos:

   ```bash
   git log --oneline
   ```
2. Comparar el último commit con el anterior:

   ```bash
   git diff HEAD~1 HEAD
   ```

---

✅ **Resultado esperado:**

* Han creado un repositorio local.
* Han hecho **2 commits**.
* Han aprendido a usar `git status`, `git add`, `git commit`, `git log` y `git diff`.

---

👉 Extra haz un **tercer commit** cambiando el archivo y luego compara el primero con el último (`git diff HEAD~2 HEAD`).

