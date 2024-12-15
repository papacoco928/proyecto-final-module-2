# MODULO 2: PROYECTO FINAL

En este repositorio se encuentra el proyecto final del segundo módulo del curso *"Course Frontend"* impartido por DEV.F.

El proyecto final consiste en elaborar una página web responsiva que se adapte y se vea bien en diferentes tamaños de pantalla y dispositivos,
para así mejorar la experiencia del usuario.

En la siguiente imagen se presentan los requisitos que debe cumplir la página:

![image/Requisitos](./assets/Captura%20de%20pantalla%202024-12-14%20210021.png)

## Breakpoints de la página
La página se adapta al ancho de un dispositivo cambiando sus estilos en los siguientes puntos de quiebre:

- 480px
- 768px

**Nota:** Los breakpoints se establecen utilizando media queries y el ancho el que cambiaran los estilos siguiedo el siguiente formato: 

```
@media screen and (min-width: 480px) {
    .
    .
    .
}
```