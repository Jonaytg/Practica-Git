# Práctica Git & GitHub

* **¿Qué comando utilizaste en el paso 11? ¿Por qué?**
Utilicé "git log" para conocer el hash del commit anterior, y después "git checkout" seguido del hash. Utilicé "git checkout" ya que si hubiera utilizado "git reset" el Working Copy se hubiera movido conmigo.

* **¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**
Volví a usar la misma metología, pero esta vez con "git reflog", ya que de haber usado "git log" no me hubiera aparecido el hash de dicho commit.

* **El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**
No, ya que la rama Main se encuentra contenida en Styled, es decir, es "hija" de Styled.

* **El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**
Sí, porque la rama "htmlify" no está contenida en la rama "styled", y en uno de sus documentos hay cambios en las mismas líneas del documento.

* **El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**
No, porque a pesar de que "main" es hijo de "styled", no hay cambios en el contenido del documento, las modificaciones únicamente fueron de formato de texto.

* **¿Qué comando o comandos utilizaste en el paso 25?**
git log --graph

* **El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**
Sí, ya que main era el único "hijo" de "title", no habían ramificaciones.
 
* **¿Qué comando o comandos utilizaste en el paso 27?**
En primer lugar "git log" para ver el hash del commit al que tengo que moverme. En segundo lugar, "git reset" seguido del hash, para retroceder al commit donde no se había hecho el merge, pero sin perder los cambios del working copy.
  
* **¿Qué comando o comandos utilizaste en el paso 28?**
Tras usar el "git status" y comprobar que el working copy mantenía las modificaciones del título, utilicé un "git restore git-nuestro.md" para descartar los cambios.
  
* **¿Qué comando o comandos utilizaste en el paso 29?**
git branch -D title
  
* **¿Qué comando o comandos utilizaste en el paso 30?**
En primer lugar, "git reflog" para conocer el hash del commit en el que hicimos el merge. Posteriormente "git chekcout" seguido de dicho hash para rehacer el merge.
  
* **¿Qué comando o comandos usaste en el paso 32?**
En primer lugar, "git log" para conocer el hash del commit en el que se creó el poema, y posteriormente "git chekcout" seguido del hash.
  
* **¿Qué comando o comandos usaste en el punto 33?**
El mismo procedimiento pero con "git reflog" para conocer el hash y "git checkout" para movernos.
