¿Qué ventaja tiene registrar las dependencias del proyecto en
requirements.txt en lugar de compartir la carpeta .venv? 

R: Portabilidad, Compatibilidad y su rapida instalacion con el comando pip install -r requirements 

# Respuestas

## Pregunta de control 1

**¿Qué ventaja tiene registrar las dependencias del proyecto en requirements.txt en lugar de compartir la carpeta .venv?**

La ventaja es que `requirements.txt` permite registrar las bibliotecas que necesita el proyecto y facilita instalarlas nuevamente en otro equipo. La carpeta `.venv` es específica de un entorno y no es necesario compartirla.

## Pregunta de control 2

**¿Por qué el repositorio que tienes ahora en tu computadora no es el mismo concepto que el fork creado en GitHub?**

El repositorio local es la copia del proyecto que se encuentra en la computadora y con la que se trabaja mediante Git. El fork es una copia del repositorio que se crea dentro de una cuenta de GitHub para poder trabajar de manera independiente y posteriormente proponer cambios al repositorio original.

## 79. ¿Cómo identificaste el comando necesario cuando la práctica no lo proporcionó?

Identifiqué la acción que necesitaba realizar y después utilicé el comando de Git o Python correspondiente. También comprobé el resultado de cada operación para verificar que se hubiera realizado correctamente.

## 80. ¿Qué diferencia existe entre preparar un archivo para un commit y crear el commit?

Preparar un archivo significa agregarlo al área de preparación para indicar que formará parte del siguiente cambio. Crear el commit significa registrar oficialmente esos cambios en el historial del repositorio.

## 81. ¿Cómo puedes comprobar en qué rama estás trabajando?

Se puede comprobar consultando las ramas del repositorio y observando cuál aparece como rama activa.

## 82. ¿Cómo puedes determinar qué archivos fueron modificados antes de registrarlos?

Se puede consultar el estado del repositorio para identificar archivos nuevos, modificados o pendientes de preparar.

## 83. ¿Cómo puedes observar exactamente qué cambió dentro de un archivo?

Se pueden consultar las diferencias entre la versión anterior y la versión actual del archivo para observar exactamente las líneas que fueron modificadas.

## 84. ¿Por qué debe reconstruirse .venv después de obtener un repositorio?

Porque `.venv` no se almacena en el repositorio. Cada computadora necesita crear su propio entorno virtual y utilizar `requirements.txt` para instalar las dependencias necesarias.

## 85. ¿Qué relación existe entre requirements.txt y .gitignore?

`requirements.txt` registra las dependencias necesarias para reconstruir el entorno del proyecto, mientras que `.gitignore` evita que archivos o carpetas que no deben almacenarse, como `.venv`, sean agregados al repositorio.

## 86. ¿Por qué la colaboración se realiza desde una rama y no directamente desde main?

Porque una rama permite realizar cambios de manera independiente sin modificar directamente la rama principal. Después los cambios pueden revisarse mediante un Pull Request antes de integrarlos.

## 87. ¿Por qué una solicitud de cambios no requiere crear un Pull Request nuevo?

Porque los cambios solicitados se realizan sobre la misma rama que ya está asociada al Pull Request. Al actualizar esa rama, los nuevos cambios aparecen automáticamente en el Pull Request existente.

## 88. Después de realizar el merge en GitHub, ¿por qué todavía es necesario actualizar el repositorio local?

Porque el merge modifica el repositorio remoto en GitHub, pero la copia local todavía puede contener una versión anterior. Es necesario obtener los cambios recientes para que el repositorio local quede sincronizado con el remoto.