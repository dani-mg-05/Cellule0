<p align="center">
   <h1 align="center">Cellule0</h1>
</p>

<p align="center">
   Este proyecto pretende introducirnos a la Inteligencia de Fuentes Abiertas (OSINT)
</p>
<p align="center">
  Tendremos que encontrar un usuario en una red social y obtener información sobre él
</p>

---

## Procedimiento
### ex00
<p align="justify">
En primer lugar, nos proporcionan la siguiente captura sobre una actividad sospechosa.
</p>

![image](https://github.com/dani-mg-05/Cellule0/assets/79267920/0b7f8f5f-3165-46c1-ac89-6f14dabbf208)

<br>

<p align="justify">
Tras inspeccionar la imagen, nos damos cuenta de que se nos muestra un usuario y una contraseña, por lo que vamos a investigar a qué red social pertenece ese usuario.
</p>

![image](https://github.com/dani-mg-05/Cellule0/assets/79267920/bfb36a25-59b7-4b02-b13e-fc8b82785024)

<br>

<p align="justify">
Hay muchas páginas web que podemos utilizar para encontrar usuarios en redes sociales. En mi caso, he utilizado <a href="https://namechk.com/">namechk</a>.
</p>

![image](https://github.com/dani-mg-05/Cellule0/assets/79267920/48c4c6e8-cb4b-41d6-8aa6-3bce3f64d73b)

<br>

<p align="justify">
Al introducir el usuario (ihatetetris42), se nos muestran los dominios y los usuarios que están siendo utilizados (rojo) o no (verde). Si buscamos en las redes sociales que están siendo utilizadas, veremos que la única que nos proporciona un resultado es Twitter / X.
</p>

![image](https://github.com/dani-mg-05/Cellule0/assets/79267920/7d6da23f-86f8-42f5-9cc2-5155c9fe05d1)

<br>

---

### ex01
<p align="justify">
Ahora, nos solicitan encontrar al verdadero dueño de la cuenta debido a que esta parece falsa. Para ello, podemos fijarnos en los usuarios que sigue la cuenta, donde nos encontramos una única cuenta.
</p>

![image](https://github.com/dani-mg-05/Cellule0/assets/79267920/54ce31e5-33bb-46d1-ad6c-d1cbdb43aab3)

<br>

<p align="justify">
Si entramos en esa cuenta, nos encontramos al usuario real.
</p>

![image](https://github.com/dani-mg-05/Cellule0/assets/79267920/62b7a37a-6702-4044-aaae-433feec75946)

<br>

---

### ex02
<p align="justify">
A continuación, nos piden encontrar la ubicación del usuario. Para ello, podemos buscar otras cuentas del mismo usuario (liam_up2u) en distintas redes sociales. Si lo hacemos correctamente, veremos que el usuario tiene una cuenta de Instagram.
</p>

![image](https://github.com/dani-mg-05/Cellule0/assets/79267920/5092cf8b-094a-473b-ae05-985155ba847f)

<br>

<p align="justify">
Gracias a la única imagen que hay en la cuenta, podemos hacer una búsqueda para averiguar qué lugar es. En mi caso, he utilizado Google Lens.
</p>

![image](https://github.com/dani-mg-05/Cellule0/assets/79267920/545e836d-93e8-4395-9dab-5a450ff395aa)

<br>

<p align="justify">
Si buscamos entre los resultados, veremos que el lugar que podemos observar en la imagen se trata de una iglesia en el municipio de Argañín.
</p>

![image](https://github.com/dani-mg-05/Cellule0/assets/79267920/bb76d8de-4139-48a3-92a9-9c6c08a18c75)

<br>

---

### ex03
<p align="justify">
Por último, nos solicitan el modelo de teléfono con el que se tomó la imagen. Si inspeccionamos la fotografía, encontraremos el resultado en la cabecera, tratándose de un Xiaomi Redmi Note 8T.
</p>

![image](https://github.com/dani-mg-05/Cellule0/assets/79267920/2cad832b-4f96-4eb2-b04e-ec2491c18713)

