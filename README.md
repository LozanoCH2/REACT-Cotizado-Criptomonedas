# Cotizador de Criptomonedas - React y TypeScript

Este proyecto es una aplicación web que permite cotizar el valor actual de diferentes criptomonedas en tiempo real. Fue desarrollado con **React** y **TypeScript**, integrando herramientas modernas como **Axios**, **Zustand**, y **Zod** para la conexión con la API de **CryptoCompare**.

## Tabla de Contenidos

- [Descripción del Proyecto](#descripción-del-proyecto)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Instalación](#instalación)
- [Funcionalidades](#funcionalidades)
- [Aprendizajes Clave](#aprendizajes-clave)
- [Créditos](#créditos)

---

## Descripción del Proyecto

El **Cotizador de Criptomonedas** permite al usuario:

1. **Seleccionar una moneda y una criptomoneda**: La aplicación muestra una lista de monedas fiduciarias y criptomonedas disponibles.
2. **Obtener información detallada**: Muestra los siguientes datos:
   - Precio actual de la criptomoneda.
   - Precio más alto y más bajo de las últimas 24 horas.
   - Variación porcentual en las últimas 24 horas.
   - Hora de la última actualización de la información.

La integración con la API de **CryptoCompare** se realizó utilizando **Axios** para las solicitudes HTTP, mientras que **Zod** se empleó para la creación de esquemas que validan los datos de la API y aseguran la integridad de la información en la aplicación.

---

## Tecnologías Utilizadas

- **React**: Biblioteca para la creación de interfaces de usuario.
- **TypeScript**: Tipado estático para mejorar la calidad y seguridad del código.
- **Tailwind CSS**: Framework CSS para diseño moderno y responsivo.
- **Axios**: Cliente HTTP para gestionar la conexión con la API de CryptoCompare.
- **Zustand**: Librería para la gestión del estado de la aplicación de manera sencilla y escalable.
- **Zod**: Herramienta para la creación y validación de esquemas de datos.

---

## Instalación

1. Clona este repositorio:

   ```bash
   git clone https://github.com/lozanoCH2/REACT-Cotizado-Criptomonedas.git
   ```

2. Navega al directorio del proyecto:

   ```bash
   cd cotizador-criptomonedas
   ```

3. Instala las dependencias:

   ```bash
   npm install
   ```

4. Configura tu API Key de CryptoCompare:

   - Crea un archivo `.env` en la raíz del proyecto.
   - Añade tu clave de API:
     ```
     REACT_APP_CRYPTOCOMPARE_API_KEY=tu_api_key
     ```

5. Inicia el servidor de desarrollo:
   ```bash
   npm run dev
   ```

---

## Funcionalidades

- **Selección de Moneda y Criptomoneda**: Lista desplegable para seleccionar las opciones deseadas.
- **Cotización Detallada**:
  - Precio actual de la criptomoneda en la moneda seleccionada.
  - Precio más alto y más bajo de las últimas 24 horas.
  - Variación porcentual en las últimas 24 horas.
  - Hora de la última actualización de los datos.
- **Diseño Responsivo**: Interfaz adaptable a dispositivos móviles y de escritorio.

---

## Aprendizajes Clave

Este proyecto me permitió profundizar en varios aspectos importantes del desarrollo con React y TypeScript, como:

1. **Conexión con APIs utilizando Axios**: Aprendí a estructurar servicios para gestionar solicitudes y respuestas de manera eficiente.
2. **Validación de Datos con Zod**:
   - Creación de esquemas para validar y tipar datos provenientes de la API de manera precisa.
   - Prevención de errores al manejar datos dinámicos en la aplicación.
3. **Gestión del Estado con Zustand**: Integración de Zustand para manejar el estado global de la aplicación, lo que mejoró la organización y escalabilidad del proyecto.
4. **Consumo de APIs en Tiempo Real**: Comprendí cómo consumir y procesar datos en tiempo real desde una API externa.
5. **Diseño Moderno con Tailwind CSS**: Mejoré mis habilidades en diseño responsivo utilizando un enfoque basado en utilidades.
6. **Mejoras en la Arquitectura del Proyecto**: Estructuración del código para separar lógica, servicios, y componentes de manera eficiente.

---

## Créditos

Este proyecto fue desarrollado como parte del curso **React y TypeScript** impartido por **codigoconjuan**. Agradezco al curso por las enseñanzas y el enfoque práctico en el desarrollo con estas tecnologías.

- [Curso de React y TypeScript - codigoconjuan](https://codigoconjuan.com)

---

## Enlace al Proyecto

Puedes probar el proyecto en el siguiente enlace:  
🔗 **[Cotizador de Criptomonedas](https://cryptomonedas-react-typescript.netlify.app)**

---

Este proyecto me ayudó a consolidar conocimientos sobre consumo de APIs, validación de datos, y la gestión eficiente del estado en aplicaciones React. ¡Espero que lo disfrutes y encuentres útil la funcionalidad de la aplicación!
