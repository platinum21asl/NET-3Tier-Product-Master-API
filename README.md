# 📦 Enterprise Product Master API (3-Tier Architecture)

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![.NET Web API](https://img.shields.io/badge/.NET_Web_API-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![3-Tier Architecture](https://img.shields.io/badge/Architecture-3--Tier-0052CC?style=for-the-badge)

## 📌 Project Description
**Enterprise Product Master API** is a robust backend web service built using **C#** and **.NET**. This project serves as a dedicated catalog and master data management system for products. 

The core highlight of this repository is its strict adherence to a classic **3-Tier Architecture**, ensuring a clean separation of concerns among HTTP routing, business logic, and database operations. It acts as an excellent foundational boilerplate for scalable enterprise backend systems.

## 🏛️ Architectural Structure
To maintain scalability, security, and clean code principles, the solution is cleanly divided into three distinct layers:

- 🌐 **`PS2-API-MstProduct` (Presentation Layer / API):** The main entry point of the application. It contains API Controllers, handles incoming HTTP requests/responses, and manages endpoint routing.
- ⚙️ **`PS2-BAL` (Business Access Layer):** The core of the system where all business rules, validations, and custom data processing logics are processed. It acts as a bridge between the API and the data layer.
- 🗄️ **`PS2-DAL` (Data Access Layer):** Dedicated entirely to database communications. It executes SQL queries, handles data retrieval, and maps database tables to application models.

## 🛠️ Tech Stack
- **Backend Language:** C#
- **Framework:** .NET Web API
- **Architecture:** 3-Tier Layered Architecture
- **Data Access:** ADO.NET / Entity Framework (Implementation specific)

## 🚀 Getting Started

### Prerequisites
- Visual Studio 2022 (or VS Code with appropriate .NET extensions)
- [.NET SDK](https://dotnet.microsoft.com/download)
- SQL Server (for database connectivity)

### Installation & Setup
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/platinum21asl/PS2-API-MstProduct.git](https://github.com/platinum21asl/PS2-API-MstProduct.git)
2. Open the Solution PS2-API-MstProduct.sln file in Visual Studio.
3. Locate the connection string within the configuration file (Web.config or appsettings.json within the API layer) and Update the Data Source to point to your local SQL Server instance.
4. Set PS2-API-MstProduct as the Startup Project.

Maintained by Daniel Renato to demonstrate highly decoupled backend software engineering.
