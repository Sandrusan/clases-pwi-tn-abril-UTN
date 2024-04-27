# Si empezamos desde cero:

    *git init
    *git add .
    *git commit -m "comentario x"
    *git branch -M main
**Debemos crear un repo en github:**

    *git remote add origin https://github.com/Sandrusan/clases-pwi-tn-abril-UTN.git
    *git push -u origin main

Listo, con esto tenemos nuestro repo en github con lo que hayamos subido

# Si estoy actualizando:
    git add .
    git commit -m "comentario x"
    git push

# ACLARACIONES

**Si me equivoque al poner el git remote usamos el comando** 

    git remote set-url origin <URL_CORRECTA>

**Podemos usar git status para obtener una informacion detallada del estado de nuestro repo**