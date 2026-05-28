# BEAUTY_STUDIOV

Beauty Studio es una tienda presencial y virtual de productos cosméticos capilares, faciales y de maquillaje. El proyecto busca automatizar procesos como el control

de inventario, stock, ventas y generación de reportes, mejorando la organización, seguridad de la información y atención al cliente mediante roles y permisos.

# PROYECTO GRUPAL

Enlace del repositorio: https://github.com/mariacamila-ctrl/BEAUTY_STUDIO.git

Nombre de la empresa: BEAUTY_STUDIO

Sector Económico: Sector terciario ( comercio y prestación de servicios )

Nombre del grupo: Los Gálacticos

Nombre de los integrantes:

* María Camila Sánchez

* Victor Alejandro Pantoja

* Carlos Santiago Achipiz

## Identificación del problema:

Beauty Studio actualmente maneja la información del negocio de manera manual, especialmente en procesos como el inventario, el control de stock, las ventas y la realización

de reportes. Esto ha generado diferentes inconvenientes, como errores en los registros, pérdida de información y demoras al momento de buscar datos o atender a los clientes.

Además, al no contar con un sistema organizado, se dificulta llevar un control claro de los productos disponibles y de las ventas realizadas, afectando la eficiencia y el buen

funcionamiento del negocio.

## Solución propuesta:

Para solucionar esta problemática, se propone desarrollar e implementar un sistema automatizado que permita registrar y administrar toda la información de forma más rápida,

segura y organizada. Con este sistema se podrá mejorar el control del inventario, automatizar las ventas y generar reportes de manera más eficiente, reduciendo errores y

optimizando el tiempo de trabajo. También se implementará un manejo de roles, donde cada usuario tendrá permisos y funciones específicas dentro del sistema según su responsabilidad.

## ¿Qué hace el sistema?

El sistema de Beauty Studio permite gestionar y automatizar los procesos principales del negocio, como el registro de productos, el control de inventario y stock, las ventas y

la generación de reportes. Además, organiza la información de manera segura y rápida, evitando errores y pérdidas de datos. También cuenta con un sistema de roles, donde cada

usuario tiene funciones y permisos específicos según su cargo, permitiendo un mejor control y administración dentro de la plataforma. Gracias a esto, se mejora la atención al

cliente, la organización del negocio y la eficiencia en los procesos diarios.

El sistema deberá hacer lo siguiente:

* Registrar productos ( nombre, código, precio, cantidad )

* Actualización de inventario y stock en tiempo real

* Generar reportes ( mensuales y anuales )

* Registrar las ventas realizadas dentro de la tienda

* Organizar y almacenar la información de forma segura

* Reducir errores y pérdidas de información

* Mejorar la rapidez en la atención al cliente

* Permitir el acceso mediante roles y permisos de usuario

* Asignar funciones específicas según el cargo de cada usuario dentro del sistema

# 📥 ENTRADAS ( Inputs )

## 1. ¿Qué datos recibe el sistema?
 
El sistema recibe información relacionada con el funcionamiento del negocio, por ejemplo:

Datos de productos:

* Código del producto

* Nombre

* Categoría

* Marca

* Precio

* Cantidad en stock

* Fecha de ingreso

Datos de ventas:

* Producto vendido

* Cantidad

* Precio total

* Fecha de venta

* Método de pago

Datos de usuarios:

* Nombre

* Correo

* Contraseña

*Rol dentro del sistema

Datos de clientes:

* Nombre

*Número de contacto

* Historial de compras

## 2. ¿Quién ingresa los datos?

Los datos son ingresados por los usuarios del sistema según su rol:

Administrador:

* Registra productos

* Gestiona usuarios

* Consulta reportes

* Actualiza inventario

Vendedor/Cajero:

* Registra ventas

* Consulta productos

* Actualiza información básica de ventas

## 3. ¿Qué tipo de datos maneja el sistema?

El sistema maneja diferentes tipos de datos, como:

Texto: Nombres, categorías, correos, marcas y descripciones

Números: Precios, cantidades, códigos, stock y totales de venta

Fechas: Fecha de ventas, ingresos de productos y reportes

## ¿Qué hace el sistema con las entradas?

Además de recibir datos, el sistema también:

* Valida que la información esté correcta

* Guarda la información automáticamente

* Actualiza el inventario en tiempo real

* Genera reportes automáticos

Protege la información según los permisos de cada usuario

# 🛠️ PROCESOS ( Throughput )

## 1. ¿Qué hace el sistema con esos datos?

El sistema procesa la información ingresada para organizar y controlar las actividades del negocio. Con estos datos,

el sistema administra productos, registra ventas, actualiza el inventario y genera reportes para facilitar el manejo de la información.

## 2. ¿Valida los datos?

Sí. El sistema verifica que la información ingresada esté correcta y completa antes de guardarla. Esto ayuda a evitar errores

en registros de productos, ventas o usuarios.

Por ejemplo:

* Verifica que no falten datos obligatorios

* Comprueba que los precios y cantidades sean válidos

* Evita registros duplicados

## 3. ¿Calcula?

Sí. El sistema realiza cálculos automáticos relacionados con las ventas y el inventario.

Por ejemplo:

* Calcula el total de una venta

* Actualiza automáticamente el stock disponible

* Calcula cantidades de productos vendidos

* Genera totales en reportes

## 4. ¿Guarda la información?

Sí. El sistema almacena toda la información de manera automática y segura en la base de datos.

Entre la información guardada se encuentra:

* Productos registrados

* Ventas realizadas

* Datos de usuarios

* Información de clientes

* Reportes e historial de movimientos

# 📤 SALIDAS ( Outputs )

## 1. ¿Qué obtiene el usuario?

El usuario obtiene información organizada y actualizada sobre el funcionamiento del negocio. Puede consultar productos disponibles,

inventario, ventas realizadas, reportes y datos registrados dentro del sistema de manera rápida y sencilla.

## 2. ¿Qué genera el sistema?

El sistema genera diferentes resultados y reportes automáticamente para facilitar el control del negocio.

Por ejemplo:

* Reportes de ventas

* Reportes de inventario

* Historial de productos

* Facturas o comprobantes de venta

* Actualización automática del stock

* Información de usuarios y clientes

## 3. ¿Permite tomar decisiones?

Sí. El sistema ayuda a tomar decisiones gracias a la información y reportes que genera. Esto permite identificar productos más vendidos,

controlar el inventario, conocer las ventas realizadas y detectar posibles faltantes o problemas dentro del negocio. De esta manera,

se mejora la organización y la administración de la tienda.

# 👥 USUARIOS Y ROLES

## 1. ¿Quién usa el sistema?

El sistema es utilizado principalmente por el administrador y el vendedor/cajero de la tienda. Cada usuario ingresa al sistema

para realizar diferentes actividades relacionadas con el manejo del negocio.

## 2. ¿Todos hacen lo mismo?

No. Cada usuario cumple funciones diferentes dentro del sistema según su rol.

🔒 Administrador:

* Gestiona productos

* Controla inventario y stock

* Administra usuarios

* Consulta reportes

* Supervisa la información del sistema

🔓 Vendedor/Cajero:

* Registra ventas

* Consulta productos disponibles

* Atiende clientes

* Actualiza información básica relacionada con ventas

## 3. ¿Hay permisos?

Sí. El sistema cuenta con permisos y roles de usuario para controlar el acceso a las funciones de la plataforma.

Esto permite que cada usuario solo pueda ingresar a las opciones que le corresponden según su cargo, mejorando la seguridad

y organización de la información.

# 📌 INFORMACIÓN MANEJADA

## 1. ¿Qué datos son críticos?

Los datos más importantes para el sistema son aquellos relacionados con el funcionamiento y control del negocio,

ya que permiten llevar una administración correcta de la tienda.

Entre ellos se encuentran:

* Información de productos

* Inventario y stock disponible

* Registro de ventas

* Datos de usuarios

* Información de clientes

* Reportes del sistema

## 2. ¿Qué no se puede perder?

La información que no se puede perder es principalmente el registro de ventas, el inventario y los datos de los productos,

ya que estos son fundamentales para el control del negocio. También es importante conservar la información de usuarios y reportes,

debido a que permiten llevar seguimiento de las actividades realizadas dentro del sistema y mantener la organización de la tienda.

# OBJETIVOS DEL SISTEMA

## 1. ¿Qué problema soluciona?

El sistema busca solucionar los problemas que existen en el manejo manual de la información dentro del negocio, como errores en el inventario,

pérdida de datos, desorganización en las ventas y demoras en la atención al cliente. Además, permite llevar un mejor control del stock, 

los productos y los reportes de manera automática y segura.

## 2. ¿A qué nivel de decisión impacta el sistema?

El sistema impacta principalmente en el nivel administrativo y operativo del negocio, ya que ayuda a organizar la información,

mejorar el control de las actividades diarias y facilitar la supervisión de productos, ventas e inventario, pero tambien puede impactar

a los siguientes:

Nivel operativo:

Que ya lo mencionamos, que es el sistema que impacta directamente en las actividades diarias del negocio, como el registro de ventas, 

actualización del inventario, control del stock y atención al cliente. Ayuda a que los procesos sean más rápidos, organizados y con menos errores.

Nivel táctico:

El sistema permite supervisar y controlar mejor la información del negocio mediante reportes de ventas, inventario y productos más vendidos. 

Esto ayuda a tomar decisiones relacionadas con la reposición de productos, control de pérdidas y organización del trabajo de los usuarios.

Nivel estratégico:

El sistema contribuye al crecimiento y mejoramiento del negocio a largo plazo, ya que facilita el análisis de la información y permite tomar

decisiones más importantes para el futuro de la tienda, como mejorar la administración, aumentar la eficiencia y ofrecer una mejor atención al cliente.

## 3. ¿Qué decisiones permitirá tomar?

El sistema permitirá tomar decisiones relacionadas con:

* Control del inventario y stock

* Reposición de productos

* Seguimiento de ventas

* Identificación de productos más vendidos

* Organización del trabajo de los usuarios

* Mejoras en la atención al cliente

## 4. ¿Qué pasaría si no existiera ese sistema?

Si el sistema no existiera, la tienda seguiría manejando la información de manera manual, aumentando el riesgo de errores, pérdida de datos y

desorganización. Además, los procesos serían más lentos, dificultando el control del inventario, las ventas y la generación de reportes, lo que 

afectaría el funcionamiento y crecimiento del negocio.

# OBJETIVOS GENERALES

## objetivo general:

Desarrollar un sistema automatizado que permita gestionar de manera eficiente el inventario, las ventas, el stock y los reportes de la tienda,

mejorando la organización de la información, reduciendo errores y optimizando la atención al cliente.

## Objetivos específicos:

Automatizar el registro y control de productos, ventas e inventario para evitar pérdidas de información y mejorar la organización del negocio.

Implementar un sistema de roles y permisos que permita controlar el acceso de los usuarios según sus funciones dentro de la plataforma.

## Nivel de decisión principal que impacta:

El sistema impacta principalmente el nivel operativo, ya que mejora las actividades diarias del negocio como el control de inventario, registro de

ventas y atención al cliente. Sin embargo, también apoya decisiones tácticas mediante reportes e información organizada.

## Características críticas que debe cumplir

* Registrar información de forma automática y segura.

* Actualizar el inventario en tiempo real.

* Generar reportes de ventas e inventario.

* Contar con roles y permisos de usuario.

* Reducir errores y pérdida de información.

* Facilitar el acceso rápido a los datos.

## ¿Qué decisión permitirá tomar?

El sistema permitirá tomar decisiones relacionadas con el control del inventario, reposición de productos, seguimiento de ventas, organización de

usuarios y mejora de los procesos del negocio para brindar una mejor atención al cliente.

# MAPA ORGANIZACIONAL

<img width="1023" height="764" alt="image" src="https://github.com/user-attachments/assets/41a10841-33b1-4c75-90cf-8cfe2e827201" />

# MAPA UML

<img width="734" height="639" alt="image" src="https://github.com/user-attachments/assets/576f9774-0a49-432e-b8c7-5d798e7c52e1" />

# Interfaz de BEAUTY_STUDIO

https://1drv.ms/w/c/35260f6afc53de7b/IQCWZEJNeOaIT6y3exHYMVW0ASRJOpiNjP2N-_O_IOlCbQo?e=u21HAQ

