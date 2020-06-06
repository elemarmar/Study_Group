# Sesión 1: Contenidos

## Maneras de posicionar contenido/elementos en una página

- Qué maneras se os ocurren de controlar la organización de contenido/elementos de una página?
  - sistemas de layout: flexbox, grid
  - posicionamiento
  - contenido generado: `:before` & `:after`
  - floats
  - utilizando inline-blocks

## Automatización de tareas

- ¿Qué es gulp? ¿En qué lenguaje está escrito?
- ¿Qué es node? ¿qué es npm?
- ¿Cómo instalar paquetes de node?
- ¿Qué nos permite hacer gulp? Dadme ejemplos
- ¿cuá es la diferenca entre package.json y gulpfile.js?
- ¿Qué es la carpeta node_modules?
- ¿Cómo instalar los pquetes de package.json? ¿Puedo añadir yo más paquetes en ese archivo escribiendo?
- Quiero crear tareas para automatizar cosas en gulp, ¿Qué hago?
- Estructura general de una tarea de gulp
- ¿Cómo correr esa tarea?
- Cuando en el adalab starter kit escribimos en la terminal "npm start" ¿qué estamos haciendo?

## Sass

- ¿Qué es Sass?
- ¿Qué es un preprocesador?
- ¿Qué tipos de archivos se manejan en Sass?
- ¿Por qué utilizar Sass?
- ¿Qué lenguaje se utiliza en Sass?
  - Tanto CSS como sintaxis de Sass.
- ¿Qué son los Sass partials?
  - archivos que empiezan con `_` y que Sass no convierte en archivos de CSS, sino que los ignora a no ser que los llames a la acción explicitamente
- ¿Cómo podemos convertir partials a CSS?
  - Con l
- ¿Describe brevemente el workflow de trabajo con Sass. Empiezas desde cero un proyecto, ¿Qué haces?
- ¿Qué es compilar? ¿Qué lenguajes compilamos en Sass?
- ¿En qué orden llamarías a los partials?
- ¿Qué es una variable? ¿Cómo se crean variables en Sass?
- Crea un ejemplo de crear una variable y llamarla. ¿Dónde guardar las variables?
- ¿Esto tiene sentido?``$page-background: $primary-light; `
- ¿Cómo mejoro este código en Sass? ¿Es válido en CSS?

```scss
.nav {
	display: flex; 
 justify-content: space-around; 
  list-style-type: none;
}
.nav li {
	width: 30%; 
  background-color: #FFEED5; 
  padding: 5px;
	text-align: center;
}
.nav a {
	text-decoration: none; 
}
```

```scss
a {
  color: blue;
}

a:hover {
  color: green;
}
```

- ¿Qué pasa si en Sass yo escribo esto? ¿Cómo se va a compilar a CSS?

```scss
a {
	color: blue; 
  :hover {
    color: green;
      }
}
```

- ¿Qué es un mixin? ¿Cuál es su estructura? (+ parámetros)
- En la estructura de nuestro proyecto, ¿dónde ponemos los mixins y por qué? ¿y las variables?
- ¿Cómo utilizamos un mixin?

---