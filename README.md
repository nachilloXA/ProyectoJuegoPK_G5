# 🃏 Proyecto Final - Programación Orientada a Objetos

## 👥 Integrantes del grupo
| Nombre completo | Carné | Usuario de GitHub | Correo de Git |
|------------------|-------|-------------------|----------------|
| [Jesus Alvarez Briceño] | [FI22028012] | [@nachilloXA] | [jalvarez10326@ufide.ac.cr] |
| [Nombre del integrante 2] | [Carné] | [@usuarioGit2] | [correo2@dominio.com] |
| [Nombre del integrante 3] | [Carné] | [@usuarioGit3] | [correo3@dominio.com] |


---

## 💻 Descripción del proyecto

Este proyecto corresponde al **proyecto final del curso de Estructura de Datos**, cuyo propósito es implementar un sistema gráfico para el manejo de una **baraja de cartas** con interfaz de usuario, aplicando principios de POO en Java.

El repositorio contiene todo el código fuente del proyecto (archivos `.java`) y **excluye los archivos compilados `.class`** según lo especificado en el archivo `.gitignore`.

---

## 🧠 Estructura del proyecto

├── src/
│ ├── Carta.java
│ ├── Mazo.java
│ ├── Mano.java
│ ├── Caja.java
│ ├── GameController.java
│ ├── MainView.java
│ └── Main.java
├── .gitignore
└── README.md

yaml
Copiar código

---

## 🧩 Editores o IDEs utilizados
- [ ] Visual Studio Code 

---

## 🌐 Referencias y recursos utilizados

| Sitio o recurso | Descripción / uso en el código |
|-----------------|-------------------------------|
| [https://docs.oracle.com/javase/](https://docs.oracle.com/javase/) | Referencia oficial de Java. |
| [https://stackoverflow.com/](https://stackoverflow.com/) | Ejemplos de manejo de eventos e interfaces gráficas. |
| [https://www.geeksforgeeks.org/](https://www.geeksforgeeks.org/) | Implementación de estructuras de datos y ejemplos de baraja. |

---

## ⚙️ Instructivo

### 🔹 Instalación
1. Asegúrese de tener instalado **Java Development Kit (JDK) versión 21 LTS**  
2. No se requieren librerías externas; se utiliza únicamente la **biblioteca estándar de Java (Swing/AWT)**.  
3. Clonar el repositorio en su entorno local:
   ```bash
   git clone https://github.com/usuario/proyecto-cartas.git
Abrir el proyecto con su IDE preferido (IntelliJ, NetBeans, etc.).

🔹 Compilación
Desde la terminal, dentro del directorio del proyecto:

bash
Copiar código
javac -d bin src/*.java
Esto generará los archivos .class en la carpeta /bin, excluidos del repositorio.

🔹 Ejecución
Ejecute el programa principal desde la terminal o el IDE:

bash
Copiar código
java -cp bin Main
Si la aplicación utiliza interfaz gráfica, asegúrese de ejecutar en entorno gráfico (no en consola pura).
