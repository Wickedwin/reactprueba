Necesario ejecutar en terminal para en el proyecto:



npm install react-validation validator
npm install redux redux-thunk
npm install --save-dev redux-devtools-extension

Ejercicios:
● Pantalla de login: Realizar un login re+(/api/login), debe contener sus validaciones correspondientes y visualización correcta de todos los datos
● Página inicial (listado de usuarios):
Para obtener la información se debe consumir: re+/api/users
Infinite scroll
Crear componente correspondiente.
Al seleccionar un usuario mostrar sidebar donde:
■ Debe permitir editar los datos. La información editada debe visualizarse en el listado.
■ Debe tener un apartado donde se muestre el listado de los post de la persona (ejemplo: jt+/posts?userId=1).
● Permitir eliminar post.
● Álbum ○ Al seleccionar el menú Albúm:
■ Mostrar el listado de los usuarios.
■ Al seleccionar un usuario, mostrar el álbum de fotos del usuario(ejemplo: jt+/users/1/albums).
● Permitir realizar logout.
La estructura de la aplicación es libre.