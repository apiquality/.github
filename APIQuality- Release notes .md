**Release notes** 

\- APIQuality \-

 **Agosto 2024**

| Versión | Autor | Fecha | Cambios |
| :---- | :---- | :---- | :---- |
| v2.0.0 | [Sonia Diaz Mingo](mailto:diazmingo.sonia@gmail.com) | 30/08/24 | Documento inicial |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |

**Índice**

[1\. v2.0.0	3](\#1.-v2.0.0)

[1.1. Obtener información de los resultados de la interfaz	3](\#1.1.-obtener-información-de-los-resultados-de-la-interfaz)

[1.2. Mostrar el histórico de ejecuciones directamente en APIQuality	3](\#1.2.-mostrar-el-histórico-de-ejecuciones-directamente-en-apiquality)

[1.3. Cambiar los nombres de openapi y de repositorio	4](\#1.3.-cambiar-los-nombres-de-openapi-y-de-repositorio)

[1.4. Definir las ramas a nivel de organización	5](\#1.4.-definir-las-ramas-a-nivel-de-organización)

[1.5. Generación de openapi en un sólo documento	6](\#1.5.-generación-de-openapi-en-un-sólo-documento)

[1.6. Añadir el nombre de usuario en los commits a los repositorios	7](\#1.6.-añadir-el-nombre-de-usuario-en-los-commits-a-los-repositorios)

[1.7. Login con SAML	8](\#1.7.-login-con-saml)

[**1.8. Otras mejoras:	8**](\#1.8.-otras-mejoras:)

[1.9. Bugs resueltos	8](\#1.9.-bugs-resueltos)  
 

#  {#1.8.-otras-mejoras:}

### 

# 1\. v2.0.0 {#1.-v2.0.0}

## 1.1. Obtener información de los resultados de la interfaz {#1.1.-obtener-información-de-los-resultados-de-la-interfaz}

En la nueva versión se puede obtener información directamente de la ejecución de los stages del CI/CD. Esta opción estará disponible pulsando sobre el icono (aspa o ok) disponible en cada stage.

A continuación se muestra la información:

![](https://raw.githubusercontent.com/apiquality/.github/master/profile/assets/image1.png)

## 

## 1.2. Mostrar el histórico de ejecuciones directamente en APIQuality {#1.2.-mostrar-el-histórico-de-ejecuciones-directamente-en-apiquality}

A partir de ahora, existe una nueva opción para mostrar el histórico de ejecuciones del CI/CD directamente desde APIQuality. Esta opción estará disponible en el menú contextual disponible en la ejecución.

![](https://raw.githubusercontent.com/apiquality/.github/master/profile/assets/image2.png)

## 1.3. Cambiar los nombres de openapi y de repositorio {#1.3.-cambiar-los-nombres-de-openapi-y-de-repositorio}

A partir de ahora se podrá cambiar tanto el nombre de la api como el nombre del fichero del repositorio directamente desde la interfaz. Sólo habrá que pulsar sobre editar en la pantalla de visualización de una API:

![](https://raw.githubusercontent.com/apiquality/.github/master/profile/assets/image3.png)

Y se cambiará automáticamente en el repositorio

![](https://raw.githubusercontent.com/apiquality/.github/master/profile/assets/image4.png)

## 1.4. Definir las ramas a nivel de organización {#1.4.-definir-las-ramas-a-nivel-de-organización}

Las entornos (ramas) que se creen a nivel de organización estarán disponibles para todas las APIs, pudiendo definir ramas personales en cada API.

Sólo los administradores y api architect podrán definir ramas para todas las apis.

![](https://raw.githubusercontent.com/apiquality/.github/master/profile/assets/image5.png)

## 1.5. Generación de openapi en un sólo documento {#1.5.-generación-de-openapi-en-un-sólo-documento}

Para openapi que utilicen ficheros externos, se ha creado una nueva funcionalidad que permite generar el openapi con las referencias externas. Esta funcionalidad puede ser configurada por el administrador de organización en settings

![](https://raw.githubusercontent.com/apiquality/.github/master/profile/assets/image6.png)

o bien puede hacerse sólo sobre el fichero que estamos importando:

![](https://raw.githubusercontent.com/apiquality/.github/master/profile/assets/image7.png)

o bien se puede crear como un stage más:

![](https://raw.githubusercontent.com/apiquality/.github/master/profile/assets/image8.png)

## 1.6. Añadir el nombre de usuario en los commits a los repositorios {#1.6.-añadir-el-nombre-de-usuario-en-los-commits-a-los-repositorios}

Se ha añadido el nombre del usuario  en los commits para que se pueda visualizar quién ha realizado los cambios. Hasta el momento er al usuario genérico de APIQuality el que se mostraba sin especificar quién era el usuario de Apiquality.

![](https://raw.githubusercontent.com/apiquality/.github/master/profile/assets/image9.png)

#  Otras mejoras {#1.8.-otras-mejoras:}

## Login con SAML {#1.7.-login-con-saml}

Para las licencias enterprise se ha habilitado un nuevo frontal dónde pueden realizar login con SAML y así conectar su login corporativo.

## Otras mejoras: {#1.8.-otras-mejoras:}

A continuación se muestra un listado de pequeñas mejoras:

* Ordenar el campo de dominios al subir una nueva API  
* Se le ha dado permisos al api design para poder ver los modelos. 

## Bugs resueltos {#1.9.-bugs-resueltos}

A continuación se muestra un listado de bugs en la versión:

* Se modifica para que no muestre como editor el creador de la api.  
* Se resuelve un bug por el cual al crear una nueva rama podía coger el nombre del fichero antiguo que se había eliminado previamente.