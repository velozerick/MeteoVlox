# Analisis
___

## Objetivo General

Diseñar y construir una estación meteorológica capaz de obtener lecturas en timepo real para observar y registrar
variables atmosféricas como velocidad del viento, temperatura, humedad y presión atmosférica mediante
el uso de sensores físicos y software personalizado. El sistema servirá como plataforma base para futuros
desarrollos web, móviles y aplicaciónes de automatización.
___

## Justificación


En la actualidad, muchas personas miran al cielo sin observarlo realmente. Este proyecto busca fomentar la curiosidad y la observación activa del entorno atmosférico mediante la construcción de una estación meteorológica casera y funcional.

MeteoVlox tiene como propósito no solo proveer datos útiles en tiempo real, sino también servir como herramienta educativa y base técnica para otros sistemas. Su integración con proyectos como AstroVeloxer permitirá evaluar condiciones óptimas para observaciones astronómicas, mientras que su conexión con VeloxerGreen aportará información valiosa para decisiones automatizadas de riego agrícola.

Además, este proyecto demuestra que con componentes accesibles, documentación clara y motivación, cualquier persona puede comenzar a comprender mejor su atmósfera local y desarrollar habilidades en electrónica, programación y ciencia aplicada.

## Requisitos funcionales

- El sistema deberá medir la velocidad del viento mediante un anemómetro impreso en 3D.
- El sistema deberá registrar la temperatura y humedad relativa mediante sensores físicos.
- El sistema deberá registrar la presión atmosférica mediante un sensor barométrico.
- El sistema deberá registrar la cantidad de precipitación acumulada en milímetros mediante un pluviómetro basculante.
- El sistema deberá mostrar los datos en tiempo real mediante una interfaz local.
- El sistema deberá almacenar los valores registrados en archivos CSV o en una base de datos local (como SQLite).
- El sistema deberá actualizar las lecturas a intervalos definidos por el usuario (por ejemplo, cada segundo).


## Requisitos no funcionales

- El sistema deberá estar disponible de forma continua, operando las 24 horas del día, los 7 días de la semana (24/7).
- El sistema deberá ser compatible con sistemas operativos Linux (Raspberry Pi OS) y adaptable para otras plataformas como Windows o móviles en etapas futuras.
- El sistema deberá permitir escalabilidad mediante una arquitectura modular que facilite la integración de sensores adicionales.
- El sistema deberá mantenerse dentro de un rango de costo accesible, utilizando sensores y componentes de bajo costo, así como partes impresas en 3D.
- El código del sistema deberá estar estructurado y documentado para facilitar su mantenimiento y comprensión.
- El sistema deberá estar licenciado bajo los términos de la licencia MIT.
- El sistema deberá funcionar de manera local, sin requerir conexión permanente a internet.


