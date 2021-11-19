# Ejercicio

Sigue las siguientes instrucciones

### Parte 1
- Crea un archivo js el cual debe llevar como nombres index.js
- Crea una función asincrona la cual debe contener 2 promesas. La primera debe llamarse paises y deberas regresa en esta promesa un arreglo de objetos como se muestra a continuación
```
[
    { id: 1, nombre: 'México' },
    { id: 2, nombre: 'Peru' },
    { id: 3, nombre: 'Colombia' },
  ]
```
- Para la segunda promesa, debe llamarse estados y deberas regresa en esta promesa un arreglo de objetos como se muesyta a continuación
```
[
      { id: 1, nombre: 'Aguascalientes', idPais: 1 },
      { id: 2, nombre: 'Baja california', idPais: 1 },
      { id: 3, nombre: 'Baja california sur', idPais: 1 },
      { id: 4, nombre: 'Campeche', idPais: 1 },
      { id: 5, nombre: 'Guainía', idPais: 3 },
      { id: 5, nombre: 'Huila', idPais: 3 },
]
```
-  Obtenido el resultado de ambas promesas, deberas filtrar todos los estados que pernezcan al pais México. El resultado debera ser un arreglo con el nombre de los estados en máyusculas. Muestrarlo en consola.
