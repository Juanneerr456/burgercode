# BurgerCode

Lenguaje para la creación y organización de recetas de hamburguesas.

**Autores:** Omar Aguado Medina (24040328) y Juan Enrique Díaz Zambada (24040324)
**Universidad Autónoma de Occidente**

## Estado
v0.1: definición del lenguaje (Sprint 1). La programación en Python empieza en el Sprint 2.

## Ejemplo

```
HAMBURGUESA "La Clasica" {
  INGREDIENTE "Pan" 1 PIEZA;
  INGREDIENTE "Carne" 150 GRAMOS;
  SALSA "Especial";
  PREPARAR;
}
```

## Palabras principales
- `HAMBURGUESA`: inicia una receta
- `INGREDIENTE`: agrega un ingrediente (nombre, cantidad, unidad)
- `SALSA`: agrega una salsa (opcional)
- `PREPARAR`: finaliza la receta

Unidades: `PIEZA`, `GRAMOS`, `HOJAS`, `RODAJAS`.

## Estructura del repositorio
```
src/      código del intérprete (Sprint 2)
tests/    recetas de ejemplo y pruebas
docs/     especificación del lenguaje
recetas/  recetas guardadas
```

## Cómo ejecutar (a partir del Sprint 2)
```
python src/burgercode.py recetas/ejemplo.burger
```

## Flujo de trabajo
Cada cambio se guarda con un mensaje de commit que describe lo que se hizo.
Tablero: Por hacer, En progreso, En revisión, Hecho.
