## Integrantes
- Fernando Santos Davalos
- Harold Ramirez
- Joel Lopez
- Andrés Menchaca
- Victor Alejandro Mojo

## Requisitos del Proyecto

### 1. Objetivos del negocio

El objetivo principal del servicio es proporcionar una solución eficiente y moderna para gestionar la venta y el acceso a eventos a través de entradas digitales. Este sistema busca generar valor para los clientes al simplificar el proceso de registro, gestión y validación de entradas. Con la aplicación móvil y la landing page, los usuarios pueden registrar, almacenar y verificar entradas de eventos de manera digital, eliminando la necesidad de entradas físicas y agilizando el control de acceso mediante códigos QR. Además, la plataforma permite a los organizadores gestionar eventos de manera centralizada y en tiempo real, lo que mejora la experiencia tanto para los organizadores como para los asistentes.

### 2. Desglose de los componentes del sistema de información

#### Hardware

- **Dispositivos de acceso al MIS:** Computadoras o terminales con acceso a internet para gestionar eventos y entradas.
- **Dispositivos móviles:** Smartphones para la app móvil que permite a los usuarios almacenar y verificar entradas mediante QR.
- **Servidores en la nube:** Para almacenar la base de datos y gestionar el procesamiento de la aplicación y la landing page.

#### Software

- **Aplicación móvil:** Desarrollada con React Native y Expo, permite a los usuarios almacenar y escanear entradas.
- **Landing page:** Creada con Astro, sirve como una página promocional del servicio y proporciona detalles sobre los eventos.
- **Sistema de Información (MIS):** Desarrollado en Python, incluye un script de terminal para registrar eventos, generar y almacenar entradas en Firebase, y convertir entradas en códigos QR.
  
#### Telecomunicaciones

- **Internet de alta velocidad:** Para la comunicación entre la app, el MIS y Firebase, permitiendo el acceso en tiempo real y la sincronización de datos.
- **Protocolos de comunicación:** Uso de HTTP/HTTPS para la transmisión de datos entre la app, la landing page y el backend.

#### Usuarios

- **Organizadores de eventos:** Pueden registrar eventos, crear entradas y generar códigos QR mediante el MIS.
- **Asistentes de eventos:** Usan la app móvil para almacenar y escanear entradas digitales.
- **Personal de seguridad:** Utiliza la app para verificar la entrada de personas a los eventos.

#### Procesos y procedimientos

1. **Registro de eventos:** Los organizadores registran los detalles del evento y las entradas disponibles en el sistema.
2. **Generación de entradas:** El MIS crea una colección en Firebase, almacenando información de cada entrada (estado, ID, fecha de modificación).
3. **Creación de códigos QR:** Las entradas se convierten en códigos QR que pueden ser almacenados y verificados por los usuarios.
4. **Escaneo de entradas:** La app permite escanear entradas QR para el control de acceso en el evento.

#### Bases de datos

- **Firebase:** Almacena la información de las entradas, incluyendo el estado, ID, fecha de modificación y cualquier otra información relacionada con el evento. Firebase proporciona almacenamiento en tiempo real y una base de datos escalable.
  
#### Seguridad

- **Autenticación y autorización:** El acceso a los datos se controla mediante tokens y roles de usuario para garantizar la seguridad de la información.
- **Encriptación de datos:** Los datos sensibles, como las entradas y la información del evento, se almacenan de manera segura en Firebase con cifrado.
- **Escaneo de QR:** La app permite la verificación de entradas mediante QR, asegurando que solo los asistentes autorizados puedan ingresar.

### 3. Presupuesto inicial

El presupuesto inicial se calcula en función de la infraestructura necesaria, el desarrollo del software y los costos asociados a la comercialización del servicio.

- **Infraestructura:**
  - Servidores en la nube (Firebase, AWS o Google Cloud): $200 mensuales.
  - Dispositivos móviles para el personal de seguridad: $300 por dispositivo (suponiendo que se adquieran 10 dispositivos).
  
- **Desarrollo:**
  - Desarrollo de la app móvil en React Native: $10,000 (considerando horas de desarrollo y pruebas).
  - Desarrollo de la landing page en Astro: $2,000.
  - Desarrollo del MIS en Python: $5,000.

- **Comercialización:**
  - Publicidad online (Google Ads, redes sociales): $3,000 anuales.
  - Marketing y promoción del servicio: $2,000.

**Total inicial estimado:** $22,500.

### 4. Cuadro de costos por servicio

| Concepto                 | Costo unitario | Cantidad | Costo total |
| ------------------------ | -------------- | -------- | ----------- |
| Desarrollo de la app     | $10,000        | 1        | $10,000     |
| Desarrollo de la landing | $2,000         | 1        | $2,000      |
| Desarrollo del MIS       | $5,000         | 1        | $5,000      |
| Servidores en la nube    | $200           | 12 meses | $2,400      |
| Marketing                | $5,000         | 1 año    | $5,000      |
| **Total**                |                |          | **$24,400** |

### 5. Proyección de rentabilidad a 10 años

Se espera que el negocio crezca a medida que más eventos adopten el sistema para la gestión de entradas digitales. Con una proyección conservadora de un 15% de crecimiento anual en ingresos y una reducción de costos operativos por economías de escala, se estima que la inversión inicial se recuperará en los primeros 3 años.

**Proyección de ingresos:**

| Año  | Ingresos estimados | Costos estimados | Rentabilidad |
|------|--------------------|------------------|--------------|
| 1    | $30,000            | $24,400          | $5,600       |
| 2    | $34,500            | $25,000          | $9,500       |
| 3    | $39,675            | $26,000          | $13,675      |
| 4-10 | Incremento anual del 15% | Incremento de costos del 5% | Crecimiento continuo |

### 6. Stack tecnológico

- **Frontend móvil:** React Native, Expo.
- **Frontend web (landing page):** Astro, Typescript, Tailwind.
- **Backend:** Python (script de terminal).
- **Base de datos:** Firebase.
- **Escaneo QR:** Librerías de QR en la app móvil (por ejemplo, react-native-qrcode-scanner).

#### LInks de GitHub
- MIS
	- [4nddrs/scriptQR](https://github.com/4nddrs/scriptQR)
- Landing Page
	- [4nddrs/LandingQR](https://github.com/4nddrs/LandingQR) 
- App Movil
	 - [harold-ramirez/entradas-digitales](https://github.com/harold-ramirez/entradas-digitales "https://github.com/harold-ramirez/entradas-digitales")


