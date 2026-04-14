# Oferta Académica - UTPL

Bienvenidos al portal oficial de la oferta académica de la **Universidad Técnica Particular de Loja (UTPL)**. Este sitio está estructurado para permitir una consulta ágil y precisa de las carreras disponibles y los títulos académicos que otorga nuestra institución.

## Organización por Facultades

Seleccione una facultad para conocer su oferta académica específica:

* [Facultad de Ciencias Económicas y Empresariales](economicas.md)
* [Facultad de Ciencias Exactas y Naturales](exactas.md)
* [Facultad de Ingenierías y Arquitectura](ingenierias.md)
* [Facultad de Ciencias Sociales, Educación y Humanidades](sociales.md)
* [Facultad de Ciencias de la Salud](salud.md)

---

## Gestión del Portal (Sección Técnica)

Este sitio está construido con [MkDocs](https://www.mkdocs.org) para garantizar una gestión de contenido eficiente e institucional.

### Comandos de Administración

* `mkdocs serve` - Inicia el servidor local de pruebas (visualiza los cambios en tiempo real).
* `mkdocs build` - Compila el sitio y genera los archivos estáticos listos para producción.
* `mkdocs -h` - Muestra la ayuda de comandos.

### Estructura del Proyecto Institucional

```text
mkdocs.yml            # Archivo de configuración (aquí se define la navegación lateral).
docs/
    index.md          # Esta página principal de bienvenida.
    economicas.md     # Tabla de carreras de Economía.
    ingenierias.md    # Tabla de carreras de Ingeniería.
    salud.md          # Tabla de carreras de Salud.
    ...               # Otras facultades.