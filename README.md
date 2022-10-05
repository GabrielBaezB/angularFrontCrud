### Instalamos Angular CLi
`npm install -g @angular/cli`

### Crearmos la aplicacion Angular
`ng new name_of_your_app`

### Instalamos el servidor JSON global
`npm install -g json-server`

### Agregamos el siguiente comando para ejecutar el servidor Json en el archivo 'package.json'
`"json-run":"json-server --watch db.json"`

![image](https://user-images.githubusercontent.com/45924381/194155587-8ded42a3-4f54-484e-8e48-9a24783710f5.png)

### Ejecutamos el siguiente comando

`npm run json-run`

>Esto creara un archivo llamada db.json o nombre que usted elija al momento de agregar el comando en el archivo 'package.json'. Ahora acceda al punto de enlace de la API como 'http://localhost:3000/fruits'.

### Instalamos Bootstrap y configuramos en 'angular.json'
`npm install bootstrap`

![image](https://user-images.githubusercontent.com/45924381/194164750-4925a514-8a19-4846-8a93-774ad7cbf6e6.png)

### Creamos los modulos
`ng generate module fruits --routing`
``

### Creamos los componentes
`ng generate component fruits/home`

`ng generate component fruits/create`

`ng generate component fruits/edit`

### Creamos los servicios
`ng generate service fruits/fruits`

### Creamos la interface
`ng generate interface fruits/fruits`



