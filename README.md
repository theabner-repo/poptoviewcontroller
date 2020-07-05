# Pop to View Controller

Podría suceder que quieres ir del último *view controller* del *navigation controller* a uno que no no es el anterior y tampoco el *root*.

En este repositorio encontrarás lo visto en el video de YouTube y una solución elegante que implementé para encontrar algún view controller dentro del stack del navigation controller.

# Navigation Stack en UINavigationController

Un [*navigation controller*](https://developer.apple.com/documentation/uikit/uinavigationcontroller) es un container *view controller* que maneja uno o más *child* view controllers en una interfaz de navegación.

Un navigation controller maneja y mantiene sus child view controllers mediante un arreglo ordenado, conocido como [__navigation stack__](https://en.wikipedia.org/wiki/Stack_(abstract_data_type)). El primer view controller en el arreglo es el *root* view controller y representa el fondo del stack. El último view controller en el arreglo es el elemento más arriba del view controller, y representa el view controller actualmente en pantalla.

# Requisitos Mínimos

- Conocer la jerarquía de vistas en una app iOS
- Entender qué es un closure: Las funciones son *first class*. Las funciones son closures.
- Enteder las extensions

# Más Información
https://docs.swift.org/swift-book/LanguageGuide/Closures.html
https://swiftbycoding.dev/swift/closures/
https://alexandrefreire.com/closures/
