# 🗄️ Sistema Central SOA con WCF y C#

[![C#](https://img.shields.io/badge/C%23-.NET-239120?style=for-the-badge&logo=c-sharp&logoColor=white)](https://docs.microsoft.com/en-us/dotnet/csharp/)
[![WCF](https://img.shields.io/badge/WCF-Services-5C2D91?style=for-the-badge&logo=.net&logoColor=white)](https://docs.microsoft.com/en-us/dotnet/framework/wcf/)
[![SQL Server](https://img.shields.io/badge/Microsoft%20SQL%20Server-2019-CC292B?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)](https://www.microsoft.com/sql-server)
[![XML/JSON](https://img.shields.io/badge/Data-XML%20%2F%20JSON-00599C?style=for-the-badge&logo=json&logoColor=white)](https://www.json.org/)

---

## 📝 Descripción del Proyecto

**Sistema Central SOA** es una solución empresarial desarrollada en el entorno de .NET basada en una **Arquitectura Orientada a Servicios (SOA)**. Su propósito principal es gestionar la sincronización e integración de datos distribuidos entre diferentes sedes o subsistemas corporativos, garantizando la trazabilidad, alta disponibilidad y consistencia de la información operacional.

---

## ⚙️ Funcionalidades Clave

- 🔄 **Sincronización de Datos Distribuidos:** Transferencia y consumo de servicios WCF para la integración de bases de datos heterogéneas.
- 📜 **Trazabilidad y Control de Logs:** Registro centralizado de transacciones y auditoría en formatos XML y JSON.
- 🛡️ **Manejo de Excepciones y FaultContracts:** Gestión estructurada de fallos en llamadas SOAP / WCF.
- 💻 **Interfaz de Administración:** Cliente de gestión escritorio en Windows Forms para el monitoreo de endpoints.

---

## 🏗️ Arquitectura del Sistema

El proyecto implementa los principios fundamentales de SOA:

- **Service Contracts (`[ServiceContract]`):** Definición de interfaces de comunicación desacopladas.
- **Data Contracts (`[DataContract]`):** Estructuras de datos serializables para intercambio ligero.
- **Service Layer:** Lógica de negocio en C# consumiendo procedimientos almacenados en SQL Server.
- **Persistence Layer:** Microsoft SQL Server con transacciones ACID.

---
---

## 📸 Capturas del Sistema

<p align="center">
  <b>🔑 Autenticación / Login</b><br>
  <img src="login_SOA_SISE.png" alt="Login SOA SISE" width="800"/>
</p>

<br>

<p align="center">
  <b>📊 Dashboard Principal</b><br>
  <img src="dashboard_principal_SSS.png" alt="Dashboard Principal" width="800"/>
</p>

<br>

<p align="center">
  <b>📝 Gestión de Matrícula</b><br>
  <img src="gestion_matricula_formnativo.png" alt="Gestión de Matrícula" width="800"/>
</p>

<br>

<p align="center">
  <b>📈 Módulo de Reportes</b><br>
  <img src="Reporte_SOA_SISE.png" alt="Reportes del Sistema" width="800"/>
</p>

---




## 🚀 Requisitos para Ejecución

- Visual Studio 2022 o superior con soporte para **WCF Services**.
- .NET Framework 4.8 o .NET Core con WCF Client libraries.
- Microsoft SQL Server Manager Studio (SSMS).

---

## 📬 Autor
* **John Javier Carhuachin Quispe**
* LinkedIn: [Perfil Profesional](https://www.linkedin.com/in/john-javier-32a068446/)
* Email: johncarhuaching@gmail.com
