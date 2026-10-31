# Mini juegos

Juego de plataformas en 2D hecho en equipo: el jugador salta entre plataformas, recoge monedas y esquiva enemigos y misiles.

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Swing](https://img.shields.io/badge/Swing-5382A1?style=flat-square&logo=openjdk&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)

> [!NOTE]
> Proyecto en equipo. El código completo está en las ramas de cada integrante, no en `main`.

## Ramas

| Rama | Contenido |
|---|---|
| `jordi` | Juego de plataformas completo |
| `marcos` | Versión del juego de plataformas en la carpeta `JuegoPlataforma/` |
| `develop` | Rama de integración |
| `main` | Rama principal |

## Estructura del juego

| Clase | Qué hace |
|---|---|
| `MenuPrincipal` | Menú de inicio |
| `Interfaz` | Ventana del juego |
| `GamePanel` | Bucle del juego y dibujo de la pantalla |
| `Player` | Jugador y sus movimientos |
| `Platform` | Plataformas |
| `Moneda` | Monedas que se recogen |
| `Enemy` y `Missile` | Enemigos y misiles |

## Cómo ejecutarlo

**Requisitos:** Java y Maven.

```bash
git switch jordi
mvn compile exec:java -Dexec.mainClass="gui.MenuPrincipal"
```

También se puede abrir en NetBeans o IntelliJ y ejecutar `MenuPrincipal`.
