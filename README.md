# PÁGINA WEB DE COMPONENTES PARA LA BIBLIOLAB
Está página web pretende ser una alternativa al sistema de acceso actual a la información
sobre los componentes disponibles en el BiblioLab de la ESIT en la ULL. Actualmente, esta
información está disponible en formato Google Sheets, pudiendo ser bastante confuso cuando
se pretende buscar cierto componente o cierta información al respecto.

## Pre-requisitos
Se requiere Python 3.6.9 o superior y pip3, que se pueden instalar con:
```shell
$ sudo apt-get install python3
$ sudo apt-get install python3-pip
```

## Instalación
Pasos para la instalación del software:

1. Clonar repositorio.
```shell
$ git clone https://github.com/alu0101119373/componentes.git
```

2. Instalar las dependencias del proyecto.
```shell
$ pip3 install -r requirements.txt
```

El software ya está listo para trabajar.

## Inicializar el servidor

Dando por hecho que tienes Daphne instalado, puedes arrancar la web con el siguiente comando.

```bash
daphne componentes.asgi:application
```

## Ejecución de las pruebas
Por el momento no se dispone de pruebas.

## Versionado
Todavía no disponemos de ninguna versión de este proyecto.

## Autores
- Himar Manuel Barquín Carrasco.
- Kevin Eliezer García Peña.

## Licencia
Este proyecto está bajo una licencia GPL, que se puede consular en el archivo [LICENSE](./LICENSE) del proyecto.
