
## Despliegue de apps Spring Boot en la Nube

Crear archivo `System.properties`en el proyecto con el contenido: 

```
java.runtime.version=LA QUE TENGAMOS
```

1. Crear cuenta en la web que queramos, Heroku no funciona asi que usamos Railway.app
2. Tener configurado git en el ordenador:
   1. `git config --global user.name "NUESTRO NOMBRE`
   2.  `git config --global user.mail NUESTRO MAIL`
3. Subir el proyecto a Github desde IntelliJ IDEA desde la opcion: VCS > Share project on Github
4. Desde la web que hayamos usado, crear app y elegir metodo GitHub buscando el repositorio subido
5. Habilitar deploy automatico si lo tiene y ejecutar el Deploy