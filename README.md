# Aplicación de Mascotas, RecyclerView y Action View

En el siguiente archivo se describira de manera breve las diferentes vistas y acciones que realiza el proyecto.
Este desarrollo es hecho por Diego Sebastian Camargo Lopez, Bogotà, Colombia.

## 1. Vista principal, general:

En esta imagen se podra observar lo que el usuario visualiza al ejecutar la aplicacion, haciendo uso del layout RecyclerView fue posible hacer que los elementos fueran visualizados dentro de un CardView, todos acomodados en forma de lista vertical.

![alt text](https://github.com/essebas/Coursera_Semana3_RecyclerView/blob/master/Solucion_actividad_final/pantalla_principal.PNG)


## 2. Vista principal, visualizando mas elementos, down scroll:

En esta imagen podemos observar la funcionalidad del RecyclerView. Acomodando todos los elementos que contiene el ArrayList de mascotas en la pantalla. Para este ejemplo, se trabajo con 10 objetos (Mascotas).

![alt text](https://github.com/essebas/Coursera_Semana3_RecyclerView/blob/master/Solucion_actividad_final/pantalla_principal2.PNG)


## 3. Vista principal, simulando click en FloatButton:

En esta imagen se realiza click en el elemento "FloatingActionButton", simulando su funcionalidad con un mensaje dentro de un Toast.

![alt text](https://github.com/essebas/Coursera_Semana3_RecyclerView/blob/master/Solucion_actividad_final/floatbtn_click.PNG)


## 4. Vista principal, simulando click para marcar Favorito:

En esta imagen se simula que el usuario realiza click en el boton con forma de hueso blanco, ubicado en la parte inferior izquerda del cardview. El usuario al realizar click, se mostrara un mensaje dentro de un SnackBar al mismo tiempo que se actualiza de manera dinamica la cantidad
de "Likes" que tiene la mascota y agregando la mascota a un ArrayList de mascotasFavoritas. En la parte superior derecha tambien se observa un cambio al dar click, debido a que se esta agregando un nuevo elemento en favoritos, el numero incrementa. 
(Se debe recordar que para hacer posible la simulacion, no se esta usando una base de datos, por lo que no se esta dando persistencia a los datos)

![alt text](https://github.com/essebas/Coursera_Semana3_RecyclerView/blob/master/Solucion_actividad_final/likebtn_click.png)


## 5. Vista principal, 3 mascotas en favoritos:

Con esta imagen se busca complementar lo descrito en la imagen anterior, para este caso, hemos añadido 3 mascotas a nuestra lista de favoritos.

![alt text](https://github.com/essebas/Coursera_Semana3_RecyclerView/blob/master/Solucion_actividad_final/likebtn_3click.png)


## 6. Vista de Favoritos, sin elementos:

Un requisito que debia contener la solicion de la actividad, era que al dar click en la estrella ubicada en la Toolbar de la aplicacion, nos llevara a otro activity donde se nos mostrara
todas las mascotas que hemos marcado como favorito en la activity principal. Para este ejemplo, no hemos dado "Like" a ninguna mascota, por lo que en el layout se nos indica que nuestra lista de mascotas favoritas se encuentra vacia.

![alt text](https://github.com/essebas/Coursera_Semana3_RecyclerView/blob/master/Solucion_actividad_final/pantalla_favoritos_vacia.PNG)


## 7. Vista de Favoritos, 1 elemento añadido:

Con este ejemplo estaremos mostrando el resultado a la accion que definimos en el numeral 4 del archivo, donde solamente le dabamos "like" a una mascota de la lista.

![alt text](https://github.com/essebas/Coursera_Semana3_RecyclerView/blob/master/Solucion_actividad_final/pantalla_favoritos_muestra.PNG)


## 8. Vista de Favoritos, 3 elementos añadidos:

Con este ejemplo estaremos mostrando el resultado a la accion que definimos en el numeral 5 del archivo, donde le dabamos "like" a 3 mascotas de la lista.

![alt text](https://github.com/essebas/Coursera_Semana3_RecyclerView/blob/master/Solucion_actividad_final/pantalla_favoritos_3muestra.PNG)


