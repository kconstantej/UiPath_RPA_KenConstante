Descripción:
Este proyecto tiene como objetivo automatizar proceso de contactos CNT utilizando UiPath, una plataforma líder en automatización de procesos robóticos (RPA). La automatización de tareas repetitivas y basadas en reglas permite aumentar la eficiencia operativa y reducir errores humanos.

Requisitos del Sistema:
UiPath Studio instalado (versión 2023.12.0 o superior)
.NET Framework 4.6.1 o superior
Conexión a internet para la descarga de paquetes y actualizaciones
Navegador Chrome en su ultima versión
Microsoft Excel 2016 o superior
El correo que se utilice para las notificaciones debe tener habilidato wnvio de correos por SMTP y debe ser outlook o hotmail

Requisitos Assets:
Crear un asset de tipo numerico llamado NumeroPaginas: Contiene el Número de páginas que se desea consultar, valor por defecto 20
Crear un asset de tipo texto llamado UrlCNT: contiene la url de CNT
Crear un asser de tipo credencial llamado Crd_Correo: el cual contiene los datos del correo que utilizaremos para las notificaciones (tener en cuenta que este correo debe tener habilitado el envio SMTP)


