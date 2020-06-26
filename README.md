# Maquinas-con-Azure
## Introducción
Las maquinas virtuales hoy en día son de gran utilidad para almacenar datos o trabajar en sistemas operativos totalmente diferentes o incluso los mismos con la finalidad de que todos los datos sean personales o a nivel de empresas tener la certeza de que tus datos quedaran guardados en lugar seguro y habil en cualquier momento y lugar  Microsoft ofrece un servicio para el uso de este tipo de sistemas en su plataforma Azure en la cúal se generara una máquina virtual. 
## Objetivos
### General
Crear máquinas virtuales en Microsoft Azure, conocer la plataforma los beneficios  que nos brinda para darle uso de forma continua



MANUAL DE USUARIO

En esta ocasion se puede tener dos opciones si tienes una tarjeta de crédito te diridiras a un link, caso contrario deberás entrar como estudiante teniendo en cuenta que alli también debes verificar tu cuenta si perteneces a alguna institucion, ya que se usara la cuenta educativa.
Se creo la de estudiante
la de Estudiante




2.Click en empiece gratis y se procede a crear o vincular con la cuenta del usuario.



3.Llenar todas las celdas de verificación para crear una cuenta gratis en Microsoft Azure.





4.Abrir el correo estudiantil y acceder al link para la comprobación académica de Microsoft del usuario.



5.Ya obtenida la cuenta Microsoft se procede a la creación de una máquina virtual. Click en la parte izquierda superior en el siguiente ícono.



6.Click en crear un recurso.



7.Para ejemplificar se escogió Windows Server 2016 Datacenter.Click en Windows Server 2016



8.Se abrirá una nueva ventana para configurar la máquina virtual que se escogió con anterioridad tomando en cuenta que el usuario tiene libre albedrío de configurar la máquina a su deseo y necesidades.

En la nueva ventana ir a la pestaña Datos básicos y asignar parámetros como:

8.1 Definir la suscripción en la cual el usuario esté registrado, en este caso Azure para estudiantes.

8.2 Seleccionar el grupo de recursos, en caso de no existir pulsar en el botón Crear nuevo.

8.3 Asignar un nombre a la máquina virtual la cual debe tener como máximo 15 caracteres, no incluir caracteres especiales y para esto Azure validara cada condición.

8.4 Definir la zona donde se ha de ubicar dicha máquina virtual.

La sección Tamaño se crea con los parámetros por defecto que son:

8.5 3.5 GB de memoria RAM

8.6 Un procesador virtual.

8.7 Disco de datos de 4 GB 

En la parte inferior configurar el nombre del usuario Administrador y crear una contraseña. Esta contraseña debe tener al menos 12 caracteres de largo y cumplir con los requisitos de complejidad definidos por Azure. En el campo Reglas de puerto de entrada, seleccionar la casilla Permitir los puertos seleccionados y luego seleccionar RDP 3389, HTTP, HTTPS en la lista desplegable con el fin de permitir el acceso externo a la máquina virtual. Click en siguiente.


En la siguiente sección llamada Discos, seleccionar entre alguno de los siguientes tipos de disco duro: SSD Premium, SSD Estándar, HDD Estándar. Recordar que los discos de estado sólido (SDD), ofrecen mejor velocidad de inicio, apagado y lectura/escritura. Click en siguiente.


En la pestaña Redes se puede agregar nuevos adaptadores de red y establecer nuevos rangos de IP si es necesario, en este caso se dejaron los parámetros por defecto. Click en siguiente


En la sección Administración se puede habilitar o no el uso de herramientas de control como: Diagnóstico de arranque, diagnóstico de sistema invitado, apagado automático, etc. Click en siguiente. 

En la sección Opciones avanzadas será posible añadir configuraciones, agentes, scripts o aplicaciones adicionales a través de las extensiones de máquina virtual o cloud-init. En este caso el usuario decidió no añadir. Click en siguiente.  

En la pestaña Etiquetas se puede crear nuevas etiquetas, estas son pares de nombre-valor las cuales dan la facilidad de categorizar los recursos y de este modo acceder a una facturación consolidada a través de la aplicación de la misma etiqueta en varios recursos y grupos de recursos en Azure, como es una versión gratuita no es necesario. Click en siguiente 

En la última pestaña Revisar y crear observa un resumen de la máquina de Windows Server 2016 Datacenter a crear a través del Portal Azure, click en crear 

18.Al finalizar la implementación de la máquina virtual, click en Ir al recurso. 

19.Se abre una ventana donde se observan las características de máquina virtual, dar click en Conectar y elegir la opción RDP. 

20.Click en descargar archivo RDP.  21.Click en descargar archivo RDP  22.Ingresar el usuario y la contraseña.Click en aceptar  23.Click en Si  24.Finalmente se obtiene la máquina virtual  

