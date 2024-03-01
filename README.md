```markdown
# Protocolo SNMP: Simple Network Management Protocol

El Protocolo SNMP (Simple Network Management Protocol) es un protocolo estándar de la industria para la gestión de dispositivos de red. Permite a los administradores
supervisar y controlar dispositivos de red, como routers, switches, servidores y dispositivos IoT, desde una ubicación centralizada.

## Componentes del Protocolo SNMP

El SNMP consta de tres componentes principales:

1. **Agentes SNMP**: Son programas que se ejecutan en los dispositivos de red y recopilan información sobre el estado y la actividad del dispositivo.

2. **MIB (Management Information Base)**: Es una base de datos jerárquica que almacena información sobre los parámetros y estados de los dispositivos de red. Define

la estructura de los datos que se pueden consultar o modificar mediante SNMP.

3.  **Gestor SNMP**:
Es una aplicación de software que se utiliza para gestionar y supervisar dispositivos de red. Envía solicitudes de información (GET) o instrucciones de configuración (SET) a los agentes SNMP para recopilar datos o realizar cambios en los dispositivos.

## Parámetros del Protocolo SNMP

El Protocolo SNMP utiliza varios parámetros para comunicarse entre los agentes y los gestores:

- **GET**: Solicita información específica de un agente SNMP.
- **GETNEXT**: Solicita la siguiente variable en la MIB.
- **GETBULK**: Recupera grandes cantidades de datos de la MIB.
- **SET**: Modifica los valores de las variables en la MIB.
- **TRAP**: Envía notificaciones asincrónicas desde los agentes SNMP a los gestores en respuesta a eventos importantes.

## Ejemplos de Uso de SNMP

### 1. Supervisión de Ancho de Banda

Un administrador de red puede utilizar SNMP para supervisar el ancho de banda de un router. Mediante la solicitud GET, el gestor SNMP puede obtener información sobre la cantidad de tráfico de entrada y salida en cada interfaz del router.

### 2. Gestión de Configuraciones

Con SNMP, un administrador puede cambiar la configuración de un dispositivo de red de forma remota. Por ejemplo, puede utilizar el comando SET para modificar el límite de velocidad de una interfaz en un switch.

### 3. Detección de Fallos

Los agentes SNMP pueden enviar trampas (TRAP) a los gestores cuando se produce un evento importante, como un fallo en un dispositivo o una interfaz inactiva. Los gestores pueden recibir estas notificaciones y tomar medidas apropiadas, como enviar alertas al personal de red.

## Conclusión

El Protocolo SNMP es una herramienta poderosa para la gestión de redes, que permite a los administradores supervisar, controlar y diagnosticar dispositivos de red de manera eficiente. Al comprender los componentes y parámetros del SNMP, los administradores pueden utilizar esta tecnología para mantener sus redes seguras y eficientes.
```

Este markdown proporciona una introducción básica al Protocolo SNMP, explicando sus componentes, parámetros y ejemplos de uso común en la gestión de redes.
