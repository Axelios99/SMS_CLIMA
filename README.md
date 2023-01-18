# SMS_CLIMA
Este proyecto extrae datos desde una API climatica, limpia los datos y se envian al celular de un usuario.

¿Como se hizo?
1) Se hace uso de la API de la pagina https://www.weatherapi.com
2) Se usa pandas para limpiar la data y seleccionar solamente las horas del día que lloverá-
3) Se usa el servicio de AWS "EC2" para crear ejecutar el script a cierta hora determinada.
4) Mediante el API de Twilio se envian datos al usuario definido.
