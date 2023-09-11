---
layout: post
title:  "Curso de Ruby II: Instalación del lenguaje"
tags:   Computing
date:   2023-09-01 10:12:33
---

Continuando con este curso **profesional** de Ruby (si no has visto el capítulo anterior te recomiendo hacer clic [aquí](https://elerizoinformatico.github.io/2023/08/23/curso-ruby-i/)), procederemos con la instalación del lenguaje en nuestra computadora independiente del sistema operativo que utilicemos (ya sea Windows, Linux o MacOS).

Por último, te enseñaré a utilizar la famosa **Interactive Ruby Shell** (Consola Interactiva de Ruby o IRB en su forma abreviada), la cual viene incluida en dicha instalación y nos permite ejecutar código Ruby desde la línea de comandos.

## Instalación en Windows

En Windows (cualquiera sea la versión que tengas) es bastante sencilla la instalación ya que solo debemos acceder a la página [rubyinstaller](https://rubyinstaller.org/) desde cualquier navegador y descargar la última versión disponible desde la pestaña **downloads**. Se descargará un archivo `.exe` que debemos ejecutar y luego seguir los pasos respectivos.

![Instalación de Ruby en Windows](/assets/img/InstalacionRubyWin.png)
<center>La versión más actual siempre se ubica en la primera posición (se recomienda descargar el archivo que incluye el devkit)</center>

Para corroborar que la instalación se realizó de forma exitosa, abrimos una terminal (`cmd`) y escribimos `ruby -v` o `ruby --version`:

```
C:\Users\elerizoinformatico>ruby -v
ruby 3.2.2 (2023-03-30 revision e51014f9c0) [x64-mingw-ucrt]
```

## Instalación en Linux

Para el caso de Linux, te recomiendo utilizar alguna versión de **Ubuntu** ya que es una distribución fácil de usar y además, cuenta con mucha documentación.

Lo primero que debemos hacer es instalar las dependencias para compilar Ruby, para ello abrimos una terminal (`Ctrl + Alt + T`) y ejecutamos los siguientes comandos:

```
sudo apt-get update
sudo apt-get install git-core zlib1g-dev build-essential libssl-dev libreadline-dev libyaml-dev libsqlite3-dev sqlite3 libxml2-dev libxslt1-dev libcurl4-openssl-dev software-properties-common libffi-dev
```

Mediante un administrador de versiones llamado **ASDF** instalaremos el lenguaje. Aunque existen otras formas de instalar Ruby (`rbenv` o `rvm`), te recomiendo ASDF ya que podemos gestionar la instalación de otros lenguajes como por ejemplo `Node.js`.

```
cd
git clone https://github.com/excid3/asdf.git ~/.asdf
echo '. "$HOME/.asdf/asdf.sh"' >> ~/.bashrc
echo '. "$HOME/.asdf/completions/asdf.bash"' >> ~/.bashrc
echo 'legacy_version_file = yes' >> ~/.asdfrc
echo 'export EDITOR="code --wait"' >> ~/.bashrc
exec $SHELL
asdf plugin add ruby
```

Instalamos la versión actual (3.2.2):

```
asdf install ruby 3.2.2
asdf global ruby 3.2.2
```

Por último, verificamos que la versión predeterminada coincida con la que acabamos de instalar:

```
which ruby
#=> /home/elerizoinformatico/.asdf/shims/ruby
ruby -v
#=> 3.2.2
```

Tener en cuenta que la instalación se está realizando en un equipo que cuenta con la versión **20.04** de Ubuntu por lo que, si tienes una versión distinta, te aconsejo visitar la página [GoRails](https://gorails.com/setup/ubuntu/22.04) y seleccionar la correcta.

## Instalación en MacOS

Para MacOS también consideraremos **ASDF**:

```
cd
git clone https://github.com/excid3/asdf.git ~/.asdf
echo '. "$HOME/.asdf/asdf.sh"' >> ~/.zshrc
echo '. "$HOME/.asdf/completions/asdf.bash"' >> ~/.zshrc
echo 'legacy_version_file = yes' >> ~/.asdfrc
exec $SHELL
asdf plugin add ruby
```

Instalación de la versión actual (3.2.2):

```
asdf install ruby 3.2.2
asdf global ruby 3.2.2
```

Por último, verificamos que la versión predeterminada coincida con la que acabamos de instalar:

```
which ruby
#=> /home/elerizoinformatico/.asdf/shims/ruby
ruby -v
#=> 3.2.2
```

Tener en cuenta que la instalación se está realizando en un equipo que cuenta con la versión **13** por lo que, si tienes una versión distinta, te aconsejo visitar la página [GoRails](https://gorails.com/setup/macos/13-ventura) y seleccionar la correcta.

Si durante la instalación de Ruby (en cualquier sistema operativo) tienes dudas, consultas o simplemente la terminal te arrojó algún tipo de error, no dudes en escribirme en la caja de comentarios.

<script src="https://utteranc.es/client.js"
        repo="elerizoinformatico/elerizoinformatico.github.io"
        issue-term="pathname"
        theme="icy-dark"
        crossorigin="anonymous"
        async>
</script>
