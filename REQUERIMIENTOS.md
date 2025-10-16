# Web para centro de estudiantes
---
## Requerimientos:

***Descripción del cliente***

- Nombre del cliente: Carlos Sepúlveda, Centro de Estudiantes de Derecho

***Contexto***

Yo estoy en el centro de estudiantes de Derecho, y uno de los temas que más nos cuesta es organizarnos bien con los estudiantes y también con las ideas o propuestas que van surgiendo.
Lo que pasa es que hoy por hoy todo lo hacemos por WhatsApp, mails, o formularios sueltos de Google. Entonces la info se pierde, nadie sabe bien qué cosas ya se propusieron, qué se está trabajando, o quién está a cargo de qué cosa. Por ejemplo, a veces alguien propone algo en una reunión o en el grupo de WhatsApp, y después no se sigue con la idea porque se pierde entre tantos mensajes o directamente se olvida. También hay estudiantes que quieren participar o ayudar, pero no saben cómo o ni a quién acercarse.

Nos gustaría tener una página web del centro donde se pueda centralizar todo: que la gente vea quiénes somos, qué estamos haciendo, que pueda proponer ideas, y que esas ideas no se pierdan. También si alguien quiere sumarse a algún proyecto, que vea en qué puede colaborar. Y que sea más ordenado, más transparente, y más fácil para todos. Que esté todo en un solo lugar.

No sabemos nada de programación, así que necesitamos algo que nosotros podamos manejar fácil después, sin tener que estar pidiéndole ayuda a alguien todo el tiempo. Algo claro, simple, donde nosotros podamos actualizar la información si es necesario.

---

***Problema principal***

-Falta de organización y centralización de la información, comunicación y gestión de ideas dentro del centro de estudiantes de las facultades de la universidad, lo que genera:
- Pérdida de información valiosa entre los múltiples canales (WhatsApp, E-mail o Formularios).
- Falta de seguimiento de propuestas e ideas.
- Desconocimiento sobre las personas que estan a cargo de los proyectos.
- Dificultad de nuevos estudiantes para participar.
- Falta de transparencia en las actividades del centro.
- Desconocimiento de los cargos que tienen los participantes del centro de estudiantes.

---

***Tipo de usuarios y perfiles con roles***

-Administrador (Directiva del Centro)
- Miembros directivos del centro de estudiantes
- Permisos: Gestión completa del sistema, moderación de contenido, asignación de roles
  
-Estudiante (Registrado)
- Estudiantes de la facultad registrados
- Permisos: Ver información, proponer ideas, comentar propuestas
  
-Profesor
- Docentes de la facultad
- Permisos: Ver información, comentar en propuestas, dar feedback académico

-Invitado
- Cualquier persona que visite el sitio
- Permisos: Solo lectura de información pública

---

***Funciones indispensables por Perfil***

-Administrador
- Gestionar usuarios y permisoso
- Crear y moderar propuestas/ideas
- Publicar información oficial
- Crear y cerrar encuestas
- Asignar responsables de proyectos
- Actualizar contenido estático (quiénes somos, contactos)

-Estudiante
- Registrarse en el sistema
- Proponer nuevas ideas
- Ofrecerse como voluntario en proyectos
- Ver estado de las propuestas
- Comentar ideas existentes

-Profesor
- Ver información pública
- Comentar en propuestas estudiantiles
- Recibir notificaciones de actividades relevantes

---

***Datos básicos a almacenar***

-Estudiante
- ID
- Nombre completo
- Correo electronico instuticional

-Profesor
- ID
- Nombre completo
- Correo electronico instuticional

---

***Requisitos Funcionales***

-RF01 - Autenticación y Autorización
- El sistema debe permitir registro con validación de email institucional
- El sistema debe implementar login/logout seguro
- El sistema debe asignar y verificar roles de usuario

-RF02 - Gestión de ideas
- El sistema debe permitir crear nuevas ideas/propuestas
- El sistema debe permitir comentar ideas
- El sistema debe mostar estados de las ideas (pendiente/aprobada/desaprobada)

---

***Requisitos no Funcionales***

-RNF01
- Interfaz intuitiva para usuarios no tècnicos
- Diseño responsive para desktop
- Navegacion simple y clara

-RNF02
- Panel administrativo fácil de usar sin conocimientos tècnicos
- Actualizacion de contenido sin necesidad de programacion

-RNF03
- Tiempo de respuesta rapido incluso con multiples usuarios
- Cache para contenido frecuentemente accedido
