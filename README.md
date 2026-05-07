# Blockchain Voting Simulator (Frontend Prototype)

An interactive electoral vote validation prototype based on a simulated decentralized network architecture. This project demonstrates key concepts of security, immutability, and data auditing using local storage.

## Key Features

* **Simulated Authentication:** Strict alphanumeric format validation (10-18 characters) for user identifiers.
* **Double-Spending Prevention:** Conditional logic that prevents the issuance of multiple votes by the same user.
* **Transparent Auditing (Ledger):** Administrative panel with restricted access (Token-based) that reads and displays stored transactions with timestamps.
* **Data Obfuscation:** Partial masking of user identifiers in the auditor's view to protect voter privacy.
* **Data Export:** Native generation (Blob API) of CSV reports for external analysis without relying on third-party libraries.
* **UX Accessibility:** Optimized navigation using keyboard events (Enter key) for authentication flows and modals.

## Technologies Used

* **HTML5 / CSS3:** Semantic structure and responsive design based on CSS Grid and Flexbox.
* **Vanilla JavaScript (ES6+):** Client-side logic, DOM manipulation, and event handling.
* **Web Storage API (`localStorage`):** Simulated non-relational database for maintaining application state.

## ⚠️ Legal Note / Disclaimer

This project is a **Frontend Simulator** created strictly for UI/UX demonstration and web programming logic purposes. The generated data lives exclusively in the user's local browser. It does not implement real asymmetric cryptography, smart contracts, or a peer-to-peer (P2P) network, and therefore should not be used in production environments.



# Simulador de Voto Blockchain (Frontend Prototype)

Un prototipo interactivo de validación de votos electorales basado en una arquitectura simulada de red descentralizada. Este proyecto demuestra conceptos clave de seguridad, inmutabilidad y auditoría de datos mediante el almacenamiento local.

## Características Principales

* **Autenticación Simulada:** Validación de formato alfanumérico estricto (10-18 caracteres) para identificadores de usuarios.
* **Prevención de Doble Gasto:** Lógica condicional que impide la emisión de múltiples votos por un mismo usuario.
* **Auditoría Transparente (Libro Mayor):** Panel administrativo con acceso restringido (Token-based) que lee y muestra las transacciones almacenadas con sellos temporales.
* **Ofuscación de Datos:** Enmascaramiento parcial de identificadores de usuario en la vista del auditor para proteger la privacidad del electorado.
* **Exportación de Datos:** Generación nativa (Blob API) de reportes CSV para análisis externo sin depender de librerías de terceros.
* **Accesibilidad UX:** Navegación optimizada mediante eventos de teclado (tecla Enter) para flujos de autenticación y modales.

## Tecnologías Utilizadas

* **HTML5 / CSS3:** Estructura semántica y diseño responsivo basado en CSS Grid y Flexbox.
* **Vanilla JavaScript (ES6+):** Lógica del lado del cliente, manipulación del DOM y manejo de eventos.
* **Web Storage API (`localStorage`):** Base de datos no relacional simulada para el mantenimiento del estado de la aplicación.

## ⚠️ Nota Legal / Disclaimer

Este proyecto es un **Simulador Frontend** creado estrictamente con fines de demostración de UI/UX y lógica de programación web. Los datos generados viven exclusivamente en el navegador local del usuario. No implementa criptografía asimétrica real, contratos inteligentes ni una red peer-to-peer (P2P), por lo que no debe utilizarse en entornos de producción.
