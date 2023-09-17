# master-entrega-03-Proyecto-Semilla


✅ Webpack.config
✅ Transpilar ES6 con Babel
✅ Imports
✅ Servidor web ligero (webpack-dev-server)
✅ Generacion de una build y asignacion al HTML los scripts de forma automática (HTMLWebpackPlugin)
✅ Gestión CSS
✅ Instalación librería Twitter Bootstrap
✅ Configuración SASS
✅ Refactorización de la estructura del proyecto (carpeta src).
✅ Trabajo con imágenes.
✅ Configuración React.
✅ Configuración y trabajo con CSS Modules.
✅ Typescript: entorno y diferentes escenarios.
✅ Diferentes configuraciones o perfiles de webpack (desarrollo / producción).
✅ Variables de entorno.
✅ Estadísticas de peso de los bundles (bundle analyzer).


Pasos para configurar y utilizar el proyecto:

1. Webpack Configuration (Webpack.config)
Este proyecto utiliza Webpack como su herramienta principal para la construcción y el empaquetado. La configuración de Webpack se encuentra en el archivo webpack.config.js y se ha optimizado para diferentes entornos.

2. Transpilación de ES6 con Babel
Babel se utiliza para transpilar el código ES6 a ES5 para que sea compatible con navegadores más antiguos. La configuración de Babel se encuentra en el archivo .babelrc.

3. Imports
Puedes utilizar la importación de módulos ES6 para organizar y gestionar tu código de manera más eficiente.

4. Servidor web ligero (webpack-dev-server)
El proyecto utiliza webpack-dev-server para crear un servidor de desarrollo local. Puedes iniciar el servidor con npm start y acceder a tu aplicación en http://localhost:8080.

5. Generación de una build y asignación al HTML de los scripts de forma automática (HTMLWebpackPlugin)
El plugin HTMLWebpackPlugin se encarga de generar automáticamente el archivo HTML con los scripts y vincularlos a la compilación de Webpack. El archivo de plantilla HTML se encuentra en la carpeta src.

6. Gestión de CSS
Este proyecto utiliza módulos CSS para encapsular estilos y evitar conflictos. Los archivos CSS se pueden importar directamente en los componentes de JavaScript.

7. Instalación de la librería Twitter Bootstrap
Bootstrap se ha integrado en el proyecto para facilitar el diseño y la maquetación. Puedes personalizar Bootstrap según tus necesidades en el archivo de configuración de SASS.

8. Configuración SASS
El proyecto utiliza SASS como preprocesador CSS. Los estilos se encuentran en la carpeta src/styles y se pueden personalizar según tus preferencias.

9. Refactorización de la estructura del proyecto (carpeta src)
La carpeta src contiene la estructura base del proyecto. Puedes organizar tus componentes, estilos y otros recursos de manera eficiente dentro de esta carpeta.

10. Trabajo con imágenes
Puedes gestionar y utilizar imágenes en tu proyecto. Coloca las imágenes en la carpeta src/assets y luego impórtalas en tu código.

11. Configuración de React
Si deseas utilizar React, este proyecto incluye una configuración inicial para React. Puedes empezar a desarrollar tus componentes React de inmediato.

12. Configuración y trabajo con CSS Modules
Los módulos CSS permiten un aislamiento efectivo de estilos para evitar colisiones. Se incluye soporte para CSS Modules en la configuración de Webpack.

13. TypeScript: entorno y diferentes escenarios
Si prefieres utilizar TypeScript, el proyecto también es compatible. La configuración de TypeScript se encuentra en el archivo tsconfig.json.

14. Diferentes configuraciones o perfiles de Webpack (desarrollo / producción)
Se han configurado diferentes perfiles de Webpack para los entornos de desarrollo y producción. Puedes construir tu aplicación para producción utilizando npm run build.

15. Variables de entorno
Puedes definir variables de entorno específicas en el archivo .env para gestionar configuraciones sensibles o personalizadas.

16. Estadísticas de peso de los bundles (Bundle Analyzer)
El proyecto incluye el plugin Bundle Analyzer para ayudarte a analizar el tamaño de tus bundles y optimizar tu aplicación.