# Bienvenido a Eden's Code <img src="profile/code.png" width="50" height="50" align=center alt="Code">

¡Donde la creatividad se encuentra con la tecnología para construir experiencias web excepcionales!

## Acerca de nosotros🤔

Somos una innovadora empresa de desarrollo web comprometida con la excelencia en la creación de soluciones digitales impactantes. Nuestro equipo de expertos está impulsado por la pasión por el diseño, la codificación impecable y la entrega de proyectos que superan las expectativas.

## ¿Qué hacemos? 💻

En Eden's Code, nos especializamos en:

- Desarrollo web moderno y ágil.
- Diseño de interfaces atractivas y funcionales.
- Aplicaciones web personalizadas para satisfacer tus necesidades específicas.
- Optimización de rendimiento para garantizar experiencias rápidas y eficientes.

## Tecnologías que usamos🔧

Nos apasiona mantenernos al día con las últimas tecnologías y tendencias. Algunas de las herramientas y tecnologías que amamos y utilizamos incluyen:

- HTML5 <img src="profile/html_1.png" width="30" height="30" align=center alt="HTML5">

- CSS3/Sass <img src="profile/css_1.png" width="30" height="30" align=center alt="CSS3">
- JavaScript/React  <img src="profile/js_1.png" width="30" height="30" align=center alt="JS">  <img src="profile/react.png" width="30" height="30" align=center alt="react">
- Node.js/Express <img src="profile/nodejs.png" width="50" height="45" align=center alt="node">
- MongoDb <img src="profile/mongodb.png" width="40" height="30" align=center alt="mongodb">
- Postresql <img src="profile/postgresql.png" width="25" height="25" align=center alt="postgresql">
- Mysql <img src="profile/sql.png" width="30" height="30" align=center alt="mysql">
- Git/GitHub <img src="profile/github.png" width="30" height="30" align=center alt="git">

## Colabora con nosotros 😎💲

Estamos siempre en busca de mentes creativas y apasionadas por la tecnología. Si compartes nuestra pasión por el desarrollo web y el diseño excepcional, ¡considera unirte a nuestro equipo!

## Contacto 🧑‍💻

¿Listo para llevar tu presencia en línea al siguiente nivel? ¡Contáctanos y descubre cómo podemos hacerlo juntos!

- Sitio web 🌐: https://www.edenscode.com
- Correo electrónico 📫: contacto@edenscode.com
- ¡Síguenos en [GitHub] https://github.com/Eden-s-Code para estar al tanto de nuestros proyectos!

¡Gracias por elegir Eden's Code para tus necesidades de desarrollo web! Esperamos colaborar contigo en la creación de experiencias digitales sorprendentes.


------------------------------------------------------------------------------------------------------------------------------------------------------------


# Contribuciones al Proyecto

Siguiendo estas pautas, podemos trabajar juntos para mejorar y mantener un código de alta calidad.

!!!☢️Codigo que no cumpla con las normas, será rechazado.


## Cómo Contribuir

Sé respetuoso con otros colaboradores.
Mantén la consistencia con el estilo de codificación existente.
Prueba tu código antes de enviar un Pull Request.
Documenta adecuadamente tus cambios.

### Pasos
1. **Forkea el Repositorio:** Haz un fork del repositorio a tu cuenta personal y clona tu fork en tu máquina local.

   ```bash
   git clone https://github.com/tuusuario/tuproyecto.git
   ```

2. Crea una rama para tus cambios
   ```bash
   git checkout -b nombre-de-tu-rama
   ```
   
3. Añade los archivos: Utiliza git add.

   ```bash
   git add .
   ```

4. Haz un Commit: Haz commit de tus cambios de manera descriptiva.

   ```bash
   git commit -m "Añadida nueva característica"
   ```

5. Hacer un Push: Sube tu rama con los cambios a tu fork.
    ```bash
   git push origin nombre-de-tu-rama
   ```

6. Por ultimo:
- Crea un Pull Request: Abre un Pull Request desde tu fork a la rama principal del proyecto.

- Revisión del Código: Tu Pull Request será revisado y discutido antes de ser fusionado a la rama principal.

## Reporte de Problemas
Si encuentras un problema o tienes una sugerencia, por favor crea un issue en el repositorio.


## Ramas que usaremos
⚠️recuerda que no nombrar las ramas correctamente es motivo de rechazo del merge

### feature/nueva-funcionalidad
- "feature/" para nuevas características, seguido de "nueva-funcionalidad", el cual es el nombre de la funcionalidad. Importante separar con guiones medios.

### bugfix/correccion-error-123
- "bugfix/" para correcciones de errores, seguido de "correccion-error-123", el cual es el nombre del error que se solucionó. Importante separar con guiones medios.
- Esta rama se debe crear y cuando se solucione el error debe ser eliminada

### hotfix/arreglo-urgente
"hotfix/" para arreglos rapidos y urgentes de solucionar, seguido de "arreglo-urgente", el cual es el nombre del error que se solucionó. Importante separar con guiones medios.
- Esta rama se debe crear y cuando se solucione el error debe ser eliminada
- Adicionalmente en esta rama se debe realizar un "REBASE" y NO un "MERGE"
  
### task/mejora-documentacion
- "task/" para cambiar la documentacion del proyecto, seguido de "mejora-documentacion", el cual es el nombre de los que se cambio. Importante separar con guiones medios.

### develop
- Esta rama será utilizada como un "main" para el desarrollo
- Los pull request seran opcionales en esta rama, pero se recomienda su uso

### main
- Esta es la rama principal del proyecto y la que se usará para realizar el despliegue a producción
- En esta rama es obligatorio el uso de pull request y los push directos serán bloqueados
