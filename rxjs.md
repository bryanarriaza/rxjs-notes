# RXJS

Se basa fuertemente en:
* Patrón Observer
* Patrón Iterator
* Programación funcional

## Patrones

### Observer
* Puede utilizarse: next() | error() | complete()
* **Observables:** Representa un flujo de datos, es una colección de eventos
que se puede emitir en un evento futuro.
* **Observer:** Son funciones que escuchan el flujo de datos y actuan sobre
los valores que emite el flujo.
* **Subscription:** Representa la ejecución de un Observable y también se
utiliza para cancelar la ejecución en un momento determinado.
* **Operadores:** Son funciones que permiten trabajar con el flujo de eventos
mediante programación funcional.
* **Subject:** Sirve para distribuir un Observable hacia varios Observer a la vez.
* **Schedulers:** Siren para controlar el orden de las subscripciones y el orden
o la emisión de eventos.

### Iterator
* hasNext() | next()

### Programación Funcional
* filter() : Filtra los datos de un arreglo.
* map() : Actualiza y retorna los datos del arreglo.
* reduce() : Retorna la suma de los valores de un arreglo
nececita 2 parametros `(valor acumulado, item actual)`
