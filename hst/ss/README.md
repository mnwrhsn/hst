# RM + Slack Stealing scheduler

Implementación de la política de planificación Rate Monotonic (RM) con Slack
Stealing (SS) para la administración del tiempo ocioso.

Realiza el calculo de Slack, y cada tarea imprime los valores de slack del
sistema y de todas las tareas.

El slack para planificar una tarea aperiodica que se despierta cada cierta 
cantidad aleatoria de tiempo.

Si se asigna 1 a USE_SLACK_K, el calculo de slack solo se realiza al iniciar el
planificador, y este valor es vuelto a cargar en cada fin de instancia. 