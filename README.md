# 🚀 First Contributions Practice

Bienvenido al repositorio oficial de prácticas de contribuciones con Git y GitHub.

Este proyecto ha sido diseñado para que estudiantes y nuevos desarrolladores puedan aprender y dominar los flujos básicos de trabajo en proyectos colaborativos utilizando GitHub. Aquí podrás practicar desde hacer un *fork* hasta abrir un *pull request* (PR), simulando cómo se trabaja en entornos reales de desarrollo de software.

---

## 🎯 Objetivo

El objetivo principal de este ejercicio es familiarizarte con los siguientes conceptos:

- Fork de un repositorio
- Clonado local
- Creación de ramas (branches)
- Organización de archivos por contribuyente
- Commits con mensajes adecuados
- Push al repositorio remoto
- Creación de un Pull Request (PR)
- Revisión y merge de cambios

---

## 🛠️ ¿Qué vas a hacer?

Cada contribuyente debe crear una carpeta con su **nombre de usuario de GitHub** dentro de la carpeta `/students`, y colocar allí un archivo de presentación personal. Esto simula una contribución sencilla a un proyecto open source.

---

## 📌 Pasos para contribuir

1. **Haz un fork** de este repositorio desde GitHub.

2. **Clona tu fork** en tu equipo local:
   ```bash
   git clone https://github.com/TU_USUARIO/first-contributions-practice.git
   cd first-contributions-practice
   ```

3. **Crea una nueva rama** con un nombre descriptivo:
   ```bash
   git checkout -b add-<tu-usuario>
   ```

4. **Crea una carpeta dentro de `students/` con tu nombre de usuario de GitHub**:
   ```
   students/tu-usuario/
   ```

5. **Agrega un archivo `hello.md` dentro de tu carpeta**, con una breve presentación. Por ejemplo:

   `students/tu-usuario/hello.md`
   ```markdown
   # Hello!
   My name is [Tu Nombre] and this is my first contribution 🤝
   ```

6. **Agrega tus cambios al control de versiones**:
   ```bash
   git add .
   git commit -m "Add folder for user: tu-usuario"
   ```

7. **Haz push de tu rama al repositorio remoto**:
   ```bash
   git push origin add-<tu-usuario>
   ```

8. **Abre un Pull Request** en GitHub solicitando que tu rama sea integrada en la rama principal (`main`).

---

## ✅ Reglas de contribución

- No modifiques archivos fuera de tu carpeta personal.
- Asegúrate de que tu carpeta esté correctamente nombrada con tu usuario GitHub.
- Usa mensajes de commit claros y profesionales.
- No envíes archivos innecesarios (por ejemplo, binarios o archivos generados).
- Sé respetuoso con tus compañeros y sus aportes.

---

## 🧠 Consejos adicionales

- Usa `git status` y `git log` para verificar tus cambios.
- Practica hacer `git pull` desde `upstream` para mantenerte sincronizado con la rama principal del proyecto.

---

## 📄 Licencia

Este proyecto está bajo la licencia MIT. Puedes revisarla en el archivo [`LICENSE`](LICENSE).

---

## 💬 Soporte

Si tienes alguna duda o encuentras problemas durante tu práctica, no dudes en comunicarte con tu instructor o levantar un *Issue* en este repositorio.

---

¡Gracias por participar y bienvenido al mundo del código abierto! 🌐
