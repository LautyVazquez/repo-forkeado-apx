Metodos Estaticos (Static)
Los usamos para utilizar funciones(metodos) sin necesidad de instanciar una clase.
Por ejemplo en este caso debemos crear un metodo que devuelva los productos que tengan un precioo por debajo al precio que usamos como argumento. Este metodo estara dentro de la clase Products, pero no debe ser necesario instanciar esta clase para poder utilizarlo, ya que la lista de propductos son importadas desde un archivo JSON.
Fork
utilizamos fork para poder clonar un repositorio de algun perfil de gitHub al nuestro y poder utilizarlo y hacerle cambios sin modificar el original. esta copia tiene su propio historial de commits en nuestra maquina y en nuestro gitHub.
PullRequest
Una vez realizados los cambis y commits en nuestra copia, utilizando pullRequest podemos enviar estos cambios a el repositorio original para que evalue los cambios y decida si quiere agregar nuestros commits al proyecto.


# Desafío

El objetivo de este desafío es hacer TDD (Test Driven Development) y guiarse con los tests
para que funcione el resto del código. Para esto tienen que leet los test y
procurar que las clases 'User' y 'Producto' funcionen junto con todos sus métodos

# Código

Los archivos están en la carpeta ./src

# Para inicializar este proyecto

```sh
pnpm install
```

o

```sh
yarn install
```

# Para correr los tests ejecutar

```sh
npm run test
```

En principio van a fallar. El objetivo es entender que te piden los test y
modificar el resto del código para que los tests pasen.

# Para correr los tests en modo watch (reinicia automáticamente)

```sh
npm run test:watch
```
