# Cliente GIT

_GitHub_ es un sitio web que sirve de repositorio de proyectos de programación. Pero, además de eso, no ofrece capacidades para
la construcción de aplicaciones de software. Estas se hacen localmente en el computador de cada quien, y luego se "suben" a la
plataforma para ser compartido con otros desarrolladores del proyecto o simplemente, para almacenarlos allá. El proceso de "subida"
se debe hacer con una herramienta local. Usted deberá instalar esa herramienta y presentar en el informe técnico la evidencia de
la instalación.

La herramienta se descarga de la [Página de descargas de GIT](https://git-scm.com/downloads). Escoja la versión correspondiente al
sistema operativo de su conveniencia e instálela en su computador. Luego de instalado el programa, ejecute la línea de comandos (en
Windows deberá ejecutar el programa `GIT Bash` para desarrollar los comandos que a continuación se presentan), la configuración inicial 
del programa. Esta configuración solo consistirá en indicar cuál es su nombre y correo electrónico. Los comandos a realizar son los
siguientes (no tiene que ingresar el `$`):

```
$ git config --global user.name "Escriba aqui el usuario github escogido"
$ git config --global user.email cuentacorrero@universidadean.edu.co
```

Luego, liste la configuración como corroboración que todo quedó bien instalado. Para ello, solo tiene que "entrar" el siguiente
comando en la línea de comandos:

```
$ git config --list
user.name=Su usuario github
user.email=cuentadecorreo@universidadean.edu.co
...
```

Realice una captura de pantalla de la salida del último comando, y anéxelo a su informe técnico como evidencia de la instalación del 
aplicativo GIT en su ambiente local.
