# Python-PLC-controller
Controlador de valores en PLC, almacena datos leídos para luego poder ser evaluados. En caso de detectar anomalías, el mismo sistema se encarga de enviar un mensaje mediante Telegram al usuario.

La conexion se realiza mediante MODBUS utilizando la libreria de Python 'pymodbus'. El sistema permite obtener valores de un PLC, luego de evaluar dichos valores procede en el caso de alguna anomalia a enviar mensaje al operador. Su funcion es similar a un sistema SCADA.
