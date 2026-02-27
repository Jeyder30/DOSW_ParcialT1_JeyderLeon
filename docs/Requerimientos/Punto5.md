# DOSW_ParcialT1_JeyderLeon

## Punto 5:Especifique los 2 requerimientos funcionales seleccionados en el punto anterior, siguiendo la plantilla de Análisis de requerimientos.
## crear una solicitud

## Descripción
El sistema debe permitir el poder crear la solicitud de cuentas digitales

## Cómo se ejecutará
1. El usuario da clic en Crear solicitud
2. Diligencia los campos obligatorios
3. Acepta términos y condiciones
4. Envía la solicitud para validacion
5. El sistema valida 


## Actor Principal
Usuario

## Precondiciones
- Programa habilitado para solicitud
- Aceptación de política de datos
- Conexión a internet

## Datos de Entrada
- Nombres y apellidos
- Documento de identidad
- Edad
- Correo(Opcional)
- Telefono
- Pais
- Tipo de cuenta (Ahorros o corriente)

## Datos de Salida
- Número de solicitud
- Confirmacion de validacion

## Flujo Básico
1. Ingreso a la aplicacion
2. Diligenciamiento de datos
3. aceptar politica de datos
4. Validación

## Flujo Alterno
- Campos vacíos obligatorios -> Mensaje de error
- No aceptacion de politicas de datos -> Mensaje de error
- Fallo de conexión -> Intentar nuevamente

## Reglas de Negocio
- Campos con (*) son obligatorios
- Un documento de identidad por cada tipo de cuenta
- Cumplimiento de normativa de protección de datos

# DOSW_ParcialT1_JeyderLeon

## Punto 5:Especifique los 2 requerimientos funcionales seleccionados en el punto anterior, siguiendo la plantilla de Análisis de requerimientos.
## añadir nuevas validaciones

## Descripción
El sistema debe poder añadir nuevas validaciones sin tener que afectar los demas

## Cómo se ejecutará
1. El administrador da clic en Crear nueva validacion
2. Indica el tipo de validacion
3. Indica las condiciones de la validacion
4. Indica el orden donde debe ir la validacion
5. Confirma la validacion


## Actor Principal
Administrador

## Precondiciones
- Tener acceso como administrador
- Conexión a internet

## Datos de Entrada
- Tipo de validacion
- condicion de validacion
- orden de la validacion

## Datos de Salida
- Nueva validacion
- orden de validacion

## Flujo Básico
1. Ingreso como administrador
2. Diligenciamiento de datos
3. Creacion de la validacion con los datos incluidos
4. Observar que la verificacion de la validacion

## Flujo Alterno
- Campos vacíos obligatorios -> Mensaje de error
- Errores de diligenciamiento -> Mensaje de error
- Fallo de conexión -> Intentar nuevamente

## Reglas de Negocio
- Tener acceso de administrador
- Indicar la validacion
