# DO Tagging

**Seguimiento de eventos y usuarios en un sitio web mediante la plataforma Dealer On**

## ¿Para qué sirve?

Este tipo de tracking permite entender mejor el comportamiento de los usuarios en el sitio web y optimizar la experiencia según sus acciones. El seguimiento de eventos proporciona información valiosa para mejorar la navegación, medir conversiones, y personalizar la experiencia del usuario.

Consulta el archivo de [ASC Parameter Definitions](https://docs.google.com/spreadsheets/d/1DZLmW9Cp5CA8J1py28xYM6SXRIEeEsagCIIEutjGLeU/edit?gid=0#gid=0) para conocer todas las opciones disponibles.

---

## Sobre el archivo **ASC Parameter Definitions**

El archivo incluye una lista de parámetros que se utilizan para realizar el tracking en Dealer On. Aquí se explican las columnas más importantes:

### Columnas principales

- **Field Name** (Nombre del campo):  
  El nombre de cada dato que se está rastreando, como `affiliation`, `comm_duration_seconds` o `element_type`. Algunos nombres son dinámicos y varían según el evento registrado.

- **Field Grouping** (Agrupación del campo):  
  Cada dato pertenece a una categoría o agrupación. Por ejemplo:

  - `Base`: Para datos generales.
  - `Custom User`: Para campos personalizados relacionados con el usuario.

- **Static/Dynamic** (Estático/Dinámico):  
  Indica si el valor del campo es fijo (mapeado) o dinámico, dependiendo del evento que se esté registrando.

- **Data Type** (Tipo de dato):  
  Define el tipo de valor que puede contener el campo, como texto (`string`), número (`integer`), etc. Por ejemplo, los números de teléfono deben seguir el formato `string` y utilizar la norma **E.164**.

### Restricciones de formato

Algunos campos tienen requisitos específicos de formato. Estos son algunos ejemplos:

- **Números de teléfono** (`comm_phone_number`):  
  Deben estar en formato **E.164**, el cual incluye el código de país y está limitado a 15 dígitos.

- **Campos en minúsculas**:  
  Algunos campos como `comm_outcome` o `element_state` deben escribirse en minúsculas, y los espacios deben reemplazarse por guiones bajos (`_`).

---

Este archivo es una guía fundamental para asegurar que el seguimiento de eventos y usuarios en la plataforma Dealer On sea preciso y eficiente.

### Referencias

- [ASC Parameter Definitions](https://docs.google.com/spreadsheets/d/1DZLmW9Cp5CA8J1py28xYM6SXRIEeEsagCIIEutjGLeU/edit?gid=0#gid=0)
- [Formato E.164](https://voipstudio.mx/blog/que-es-el-formato-e-164-y-como-usarlo-correctamente/)
