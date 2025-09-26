# daweb2526-u01-markdown-asm

# Título H1
## Título H2
### Título H3

*itálica*   → *itálica*  
**negrita** → **negrita**  
~~tachado~~ → ~~tachado~~

- Item 1
- Item 2
  - Subitem 2.1

1. Primer paso
2. Segundo paso


[Texto del enlace](https://example.com)  

![Texto alternativo](https://placehold.co/150)

![Imagen del repositorio](images/test.png)

> Esto es una cita

`System.out.println("Hola");`

```java
public class Hola {
  public static void main(String[] args) {
    System.out.println("Hola mundo");
  }
}
```
| Nombre | Edad | Ciudad   |
|:-------|:----:|:----------|
| Ana    |  25 | Granada   |
| Juan   |  30 | Jaén      |

[Ver historial de cambios](CHANGELOG.md)


# Ticket Logger 

Aplicación web para la gestión de incidencias.

## Características
- Registro de tickets
- Sistema de notificaciones en tiempo real
- Autenticación con JWT

## Instalación
```bash
git clone https://github.com/usuario/ticket-logger
cd ticket-logger
mvn clean install
mvn jetty:run
```
