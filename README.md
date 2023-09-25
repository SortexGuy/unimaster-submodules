# UniMaster - Administrador Universitario

## Enlazaces a los respositorios individuales

[Frontend](https://github.com/Gabo-div/frontend-hackaton-unimaster)

[Backend](https://github.com/Gabo-div/backend-hackaton-unimaster)

---

Este proyecto fue realizado en un lapso de 48 horas para el CODECHALLENGE UCAB 2023 en septiembre, bajo la temática de **_"Solucionar un problema real que hayas tenido en tu vida universitaria"_**.

## Planteamiento

Nuestra idea fue crear una página que agilice la organización y la monitorización de la vida academica universitaria.
Esta idea surgio por la complejidad que puede transmitir otras aplicaciones de gestion de notas como Notion apesar de la gran utilidad que tienen,
por esto mismo decidimos tomar funciones especificas para simplificarlas y adaptarlas al ambiente universitario de una manera más amigable.

## Empezando

### Antes de empezar

Este proyecto utiliza NodeJS asi que vamos a necesitar instalarlo.

#### Para linux

Pueden utilizar su gestor de paquetes de confiaza para instalar los paquetes `nodejs` y `npm`.

Debian/Ubuntu: `sudo apt install nodejs npm`

Arch linux: `sudo pacman -S nodejs npm`

#### Para windows

El instalador de la version estable de NodeJS se encuentra en su [pagina web](https://nodejs.org/en).

---

Para clonar este repositorio con todos los submodulos, los cuales incluyen los archivos para el backend y frontend debes de hacer uso de este comando:

`git clone --recurse-submodules https://github.com/SortexGuy/unimaster-submodules`

Una vez clonado, debemos de instalar las dependencias por lo cual deberá de ejecutar este comando dentro de la carpeta backend y frontend:

`npm i`

### Ejecutando la aplicacion

Para hacer funcionar la app debemos de ejectuar el backend y el frontend por separado al mismo tiempo, usando el siguiente comando cada uno:

`npm run dev`

Podremos encontrar la aplicación corriendo en la siguiente dirección URL desde nuestro navegador:

`localhost:3000`
