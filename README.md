Simulación de Red en Python
Descripción

Este proyecto simula una red de comunicación básica utilizando Python y programación orientada a objetos. Se modela un servidor y varios clientes (nodos) que pueden conectarse entre sí y enviar mensajes.

También se implementa una simulación de desconexión y reconexión dinámica dentro de la red.

Objetivos
Entender cómo funciona una red de comunicación.
Aplicar programación orientada a objetos.
Simular envío de mensajes entre nodos.
Representar desconexiones y reconexiones.
Estructura
Clase Nodo

Cada nodo tiene:

Un nombre
Una lista de conexiones
Métodos principales:
agregar_conexion(nodo): conecta nodos
eliminar_conexion(nodo): elimina conexiones
enviar_mensaje(mensaje): envía mensajes
recibir_mensaje(origen, mensaje): recibe mensajes
Funcionamiento
Se crean un servidor y 3 clientes.
Se conectan entre sí.
El servidor envía un mensaje inicial.
Se desconecta un cliente usando eliminar_conexion.
Se usa time.sleep() para simular un retraso.
Se muestra el mensaje:
"Simulando desconexión y reconexión dinámica..."
Se vuelve a conectar el cliente.
Se envía el mensaje final:
"¡Hola de nuevo a todos!"
Ejecución

Ejecutar el archivo con:

python Servidor.py
