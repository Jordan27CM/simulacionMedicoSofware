# Sistema Reserva de Salas 
### Integrantes
- Jordan Murillo | Seccion 1
---

![IMG-20250523-WA0001](https://github.com/user-attachments/assets/b90ce7ee-261c-4b8a-b780-669421f666c5)

## Correcion de diagrama de caso de uso
- El actor de estudiante esta conectado al caso de uso de ver el historial de otras persona cuando por temas de seguridad estos no podrian estar conectados
- El actor estudiante deberia estar conectado directamente al caso de uso de ver historial de reservas
- Y la notificacion por correo deberia estar conectado con el estudiante ya que es la parsona final a la que tiene que llegar el correo si se aprueba su solicitud
- Falta indicar las relaciones en los casos de uso si son include o extend los extend que veo son los de eliminar historial de reservas ya que es opcional y no es obligatorio, los include que veo son de agregar un modtivo de cancelacion al cancelar reserva, la notificacion de la reserva si se aprueba y la ver la consulta de disponibilidad externa 

## Correcion diagrama de clases 
- La clase reserva deveria estar asiciada al usuario ya que un usuario crea una reserva al solicitar una sala
- La clase de reserva deveria tener atrivutos de quien hizo la reserva y la sala que reservo
- El administrador deveria estar asociado a reservas ya que el administrador el que puede aprovar o desaprovar una solicitud

## Correcion diagrama de implementacion
- En la base de datos central se podrian almacenar mas datos como los mensajes de notificacion para tener un registro mas controlado
- Al navegador del estudiante le faltaria ver el estado de la solicitud para saber si su solicitud fue aprobada
- Faltaria un modulo para los administradores donde puedan recibir las solicitudes de reserva y aprovarlas o rechazarlas

Fecha Entrega: 23 - Mayo - 2025
