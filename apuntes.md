<!-- ENCABEZADOS -->
# My title
## Subtitle

<!-- FORMATOS -->

*cursive*

**Highlited**

~~Crossed~~

<!-- LISTAS -->

* Manzana
* Naranja
* Melón
  * Santa Claus melon
  * Galia Melon

1. Manzana
2. Naranja
3. Melón
    1. Piel de sapo
    2. De Galia

<!-- ENLACES -->

[Fprodrigocaro](https://fprodrigocaro.org)

<!-- CITAS -->

> Esto es una cita

<!-- Linea horizontal -->

---

<!-- CODIGO -->

`apt install apache2`

```
apt update 
apt upgrade
apt install apache2
```

```sh
#¡/bin/bash
if [ ! -d "$directorio" ]
    then
        mkdir "$directorio"
```

<!--TABLAS-->

| Nombre    | Apellido  |
|----------|--------|
|Manuel |Dominguez|
|Rosa|López|

<!-- IMAGENES-->

![Goku](https://img2.rtve.es/im/4111731/?w=900)

![Tf2](tf2.jpg)

```
---
---
---
```
<!-- ADD REPOSITORY FROM COMMAND LINE-->
echo "# markdown" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Xicobot/markdown.git
git push -u origin main

<!-- REMOVE REPOSITORY FROM COMMAND LINE-->

git remote add origin https://github.com/Xicobot/markdown.git
git branch -M main
git push -u origin main
