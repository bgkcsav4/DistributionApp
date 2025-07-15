📦 DistributionApp

DistributionApp is a Windows-based desktop application developed in C# using the .NET Framework and DevExpress UI components. It is structured with a layered architecture, separating domain logic and data access for maintainability and scalability.

---

🧩 Features

- Responsive UI using DevExpress (v19.2)
- Clean architecture with separation of concerns:
  - Domain Layer (`LatzaDB.Domain.dll`)
  - Repository Layer (`LatzaDB.Repository.dll`)
- Data visualization via layout, pivot grids, and tree lists
- Configurable through `LatzaDB.exe.config`

---

 ⚙️ Tech Stack

- Language: C#
- Framework: .NET Framework
- UI Toolkit: DevExpress v19.2 (XtraLayout, XtraTreeList, XtraPivotGrid, etc.)

---

 🚀 Getting Started

Prerequisites

- Windows OS
- [.NET Framework 4.x](https://dotnet.microsoft.com/en-us/download/dotnet-framework)
- Visual Studio

 Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/bgkcsav4/DistributionApp.git
    ```
2. Open the project in **Visual Studio**
3. Restore NuGet packages (if needed)
4. Build the solution
5. Run the application

 Configuration

Edit `LatzaDB.exe.config` to adjust settings such as database connection strings, layout preferences, or other runtime configurations.

---

 🗃 File Overview

```
DistributionApp/
├── LatzaDB.Domain.dll          # Domain/business logic
├── LatzaDB.Repository.dll      # Data access layer
├── DevExpress.*.xml            # UI components documentation
├── LatzaDB.exe.config          # Application settings
├── *.pdb                       # Debugging symbols
```

---
👤 Author

Developed by [@bgkcsav4](https://github.com/bgkcsav4)