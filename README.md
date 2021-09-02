# Monitoring_Zabbix_Windows

1. Descargar ficheros.
2. crear una carpeta llamada zabbix en disco C.
3. pegar en carpeta zabbix los archivos Zabbix_agent2.exe y zabbix_agentd2.win.conf
4. Abrir PowerShell en modo administrador.
5. Ejecutar el siguiente comando:  **c:\zabbix\zabbix_agentd2.exe --config c:\zabbix\zabbix_agentd2.win.conf --install**
6. Abrir Servicios
7. Buscar el servicio Zabbix Agent
8. Seleccionamos el servicio, click derecho y seleccionamos Iniciar.
