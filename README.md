# pr0-template
Este proyecto es creado como una plantilla para el resto de proyectos.

## Estructura del proyecto
```
prNum-Nombre
└───common
│   │   navbar.html
│   │   footer.html
│   │   ...
└───css
│   │   navbar.css
│   │   ...
└───fonts
│   │   Roboto.ttf
│	│   Roboto_bold.ttf
│   │   ...
└───img
│   │   home
│   │   │   logo.jpg
│   │   social-media
│   │   │   facebook.jpg
│   │   │   twitter.jpg
│   │   ...
└───js
│   │   mainFunctions.js
│   │   jquery.js
│   │   ...
│   index.html
```

- `commons`
	- contiene los archivos HTML comunes, utilizados en toda la aplicación web.
- `css`
	- contiene todos las hojas de estilo.
- `fonts`
	- contiene los archivos de fuentes.
- `img`
	- contiene imágenes y otros recursos multimedia
- `js`
	- contiene los archivos JS
- `index.html`
	- archivo principal HTML

## Guía de Colaboración

### Creación de Ramas

- Las ramas creadas por cada nueva función/característica `feature/nombre-del-feature` se haya bifurcado/forked desde la rama `development`
	- Nomenclatura de ramas:
		- `feature/*`
		- `bugfix/*`
		- `improvement/*`
		- `prerelease/*`
		- `release/*`
		- `master`
		- `development`
		- Tener en consideración que cuando se trabaje con GitHub Projects, el nombre de las ramas relacionadas a nuevas funciones deberán crearse así:
			- `feature/*-{NÚMERO_DE_ISSUE}`
			- Ej: `feature/pagina-inicio-01`
- Asegurarse de realizar los `push` de la siguiente manera `git push -u origin feature/nombre-del-feature`
- Asegurarse que al realizar un `Pull Request` deberá realizarse desde la rama `feature` a la rama `development` con un responsable para su revisión.
- Sólo la/las responsables técnicas deberán interactuar con la rama `master`

### Contribución en Github

- Cuando se realice una contribución al repositorio, el commit deberá ir acompañado de un mensaje, siguiendo la siguiente convención:
	- Nomenclatura de commits:
		- `fix`
		- `change`
		- `revert`
		- `style`
		- `refactor`
		- `docs`
		- `test`
		+ descripción del commit