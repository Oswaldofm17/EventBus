#EventBus: Eventos para Android

EventBus es una open-source library para Android que utiliza el patrón de publicador/suscriptor para el acoplamiento suelto. EventBus permite la comunicación central para desacoplar las clases con sólo unas pocas líneas de código, simplificando el código, eliminando las dependencias y acelerando el desarrollo de la aplicación.

![alt text](https://github.com/Oswaldofm17/EventBus/blob/master/EventBus-Publish-Subscribe.png "Logo Title Text 1")

###Sus beneficios con EventBus: ...

* Simplifica la comunicación entre componentes

* Desacopla los remitentes y receptores de eventos

* Funciona bien con Actividades, Fragmentos y hilos de fondo

* Evita las dependencias complejas y propensas a errores y los problemas del ciclo de vida es rápido; Optimizado específicamente para altas prestaciones

* Es pequeño (<50k jar)

* Está probado en la práctica por las aplicaciones con más de 100.000.000 de instalaciones

* Tiene características avanzadas como hilos de entrega, prioridades de suscriptores, etc.

Otras funciones de EventBus

* Conveniente Annotation based API: Conveniente Annotation based API: Basta con poner la anotación @Subscribe a sus métodos de suscriptor. Debido a una indexación de anotaciones de generación de tiempo, EventBus no necesita hacer reflexión de anotación durante el tiempo de ejecución de la aplicación.

* Entrega de hilos principales de Android: Al interactuar con la interfaz de usuario, EventBus puede entregar eventos en el hilo principal independientemente de cómo se publicó un evento.

* Entrega de subprocesos de fondo: si su suscriptor ejecuta tareas largas, EventBus también puede utilizar subprocesos de fondo para evitar el bloqueo de la interfaz de usuario.

* Sucesión y herencia de suscriptor: En EventBus, el paradigma orientado a objetos se aplica a clases de suceso y de evento. Digamos que la clase de eventos A es la superclase de B. Los eventos de tipo B también se publicarán a suscriptores interesados ​​en A. De forma similar, se considerará la herencia de las clases de suscriptor.

* Salto inicial: puede empezar inmediatamente - sin necesidad de configurar nada - utilizando una instancia predeterminada de EventBus disponible desde cualquier parte de su código.

* Configurable: Para ajustar EventBus a sus necesidades, puede ajustar su comportamiento utilizando el patrón de constructor.
