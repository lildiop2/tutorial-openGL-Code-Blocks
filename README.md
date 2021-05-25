# tutorial-openGL-Code-Blocks
Esse é um tutorial básico para configurar OpenGL no Code::Blocks no distro Debian 10

_by **Abdul Kevin Alexis**_

Vamos usar o terminal para fazer os comandos. É preciso reconfigurar o Code::Blocks. Seria melhor desinstalar para podermos instalar novamente.

* __Passo 1__ Faça um "apt-get update" para manter sua lista de pacotes atualizada.
~~~bash
sudo apt-get install
~~~
![Passo 1](img/update.png)

* __Passo 2__  Faça "sudo apt-get install codeblocks" para instalar o codeblock
~~~bash
sudo apt-get install codeblocks
~~~
![Alt ou título da imagem](URL da imagem)

* __Passo 3__  Faça "sudo apt-get install libc6-dbg gdb valgrind" para instalar o compilador _**GDB**_
~~~bash
sudo apt-get install libc6-dbg gdb valgrind 
~~~
![Alt ou título da imagem](URL da imagem)

* __Passo 4__ Vamos instalar a biblioteca _**FreeGlut**_
~~~bash
sudo apt-get install freeglut3 freeglut3-dev
~~~
![Alt ou título da imagem](URL da imagem)

* __Passo 5__ Vamos instalar a biblioteca _**Glew**_
~~~bash
sudo apt-get install -y libglew-dev
~~~
![Alt ou título da imagem](URL da imagem)
