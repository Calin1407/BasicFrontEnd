# Project's Structure

src / app

``Bounded Context: project``

- project

- - application
- - domain
- - - model
- - infrastructure
- - presentation
- - - views

``Logica compartida``

- shared

- - infrastructure
- - presentation
- - - views
- - - components

## project

```
Se pone para ejemplificar el bounded context de
nuestro proyecto o negocio.

Observacion: para este caso, ponemos proyecto, debido
a que no se presentaran bounded context complejos al
ser un proyecto basico de nuestro front.
```

## application

```
Casos de uso del bounded contexto
Por ejemplo, podriamos poner la busqueda, creacion,
eliminacion, etc.
```

## domain/model

```
Reglas y conceptos dentro del negocio: 
entidades, interfaces, valueobjects, commands, etc.
(EMPAQUETAMIENTO)
```

## infrastructure

```
Comunicacion con API's
```

## presentation/views

```
Visualizacion de datos relacionados 
con el bounded context
```

# ---------------------------------------------

## shared

```
Es donde se encontrara toda la logica compartida de nuestro
proyecto. Por ejemplo, cosas que se usaran en todo el Front
como cambio de idioma, inicio, page-not-found, etc.
```

## infrastructure

```
conexion de servicios necesarios en toda la aplicacion
```

## presentation

```
componentes visuales sin logica de negocio
```
