
Proyecto de Automatización en n8n. Lectura de datos de Estación Meteorologica Chivilcoy

Este proyecto contiene un flujo de trabajo (workflow) creado en n8n para automatizar procesos de toma de datos de la Estacion para enviar por mail a emisoras de radio.


Se eligió este tema porque detectamos la necesidad de enviar la información a las emisoras de radio con información completa para emitir en noticieros cada media hora o en el tiempo que estimen.

La Municipalidad de Chivilcoy cuenta con una estación meteorológica ubicada en la ciudad en el Parque Ci, cuyos datos instantáneos de los distintos valores del estado del clima se pueden ver en la pagina de la Municipalidad.

El trabajo de automatización consiste en tomar datos de la estación meteorológica ubicada en la ciudad de Chivilcoy, cada media hora, teniendo en cuenta que la reposición de datos de la estación es cada 15 min, para lograr que de esta manera no se repiten valores. Los datos se cargan en una planilla Google Sheet, agregando una nueva fila, estos datos son enviados a las emisoras de radio por correo electrónico.

Las emisoras pueden registrarse mediante una planilla de ingreso de datos por web, haciendo la solicitud al Municipio que es el titular de la Estación meteorológica.

