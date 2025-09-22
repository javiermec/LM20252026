

# 🚀 **Arranque: Instalación de Git y uso de terminales**

## 1. Instalar Git

Antes de empezar, cada alumno debe tener **Git** instalado en su equipo.

* Descarga oficial: [https://git-scm.com/downloads](https://git-scm.com/downloads)
* En Windows: seleccionad las opciones por defecto.
* En Mac/Linux: normalmente ya está preinstalado, si no, se puede instalar con el gestor de paquetes (`brew install git`, `apt install git`, etc.).

👉 Comprobad la instalación:

```bash
git --version
```

Si devuelve algo como `git version 2.x.x`, ya está listo.

---

## 2. ¿Dónde vamos a trabajar?

Podéis usar **terminales diferentes** para ejecutar Git. Todos sirven, pero cambian un poco en aspecto y en algunos comandos extra.

### 🔹 a) Terminal integrado de VS Code

* Está dentro del editor.
* Ventaja: no salís del entorno de programación.
* Se abre con:

  * Menú: **Ver → Terminal**
  * O atajo: <kbd>Ctrl</kbd> + <kbd>\`</kbd> (acento grave, encima de la tecla Tab).
* Podéis elegir el tipo de terminal desde la pestaña: **PowerShell, CMD, Git Bash, WSL…**

### 🔹 b) Git Bash (Windows)

* Se instala junto con Git.
* Es un terminal que imita al de Linux/Unix.
* Ventaja: compatible con la mayoría de ejemplos de tutoriales en Internet (que suelen estar hechos en Linux o Mac).
* Comandos típicos: `ls`, `pwd`, `clear`, además de `git`.

### 🔹 c) CMD o PowerShell (Windows)

* CMD = terminal clásico de Windows.
* PowerShell = versión más moderna y potente.
* Inconveniente: algunos comandos básicos cambian (`dir` en lugar de `ls`, `cls` en lugar de `clear`).
* Pero Git funciona igual en ambos.

### 🔹 d) Terminal en Linux o Mac

* Suele ser el más estándar.
* Usa comandos Unix como `ls`, `pwd`, `clear`.
* Git ya está integrado en casi todos los casos.

---

## 3. Resumen rápido de diferencias

* **Git Bash / Linux / Mac terminal** → usan comandos estilo Unix (`ls`, `pwd`).
* **CMD / PowerShell** → comandos estilo Windows (`dir`, `cd`, `cls`).
* **Todos** permiten usar los comandos de `git` exactamente igual (`git init`, `git add`, `git commit`, etc.).

---

👉 Para la práctica en clase usaremos **el terminal integrado de VS Code** (más cómodo) o, si prefieres, **Git Bash** por fuera (para ver el estilo Linux).

---

