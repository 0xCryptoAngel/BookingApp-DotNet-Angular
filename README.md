
# BookingApp


## 📝 Description

A web-based client-server system for booking or renting any type of resource. The system provides:

- A tree-view of all available resources
- Calendar-based availability
- Resource-specific booking rules
- User authentication
- Booking management

Business owners are given a full set of administrative features including statistics, user access management, and booking oversight.

---

## 🛠️ Technologies & Methodologies

**Frontend:**
- Angular 5
- Bootstrap
- Karma & Jasmine (unit testing)

**Backend:**
- C#, ASP.NET Core MVC
- ASP.NET Core Identity
- Entity Framework Core
- Repository Pattern
- Swagger for API documentation
- AutoMapper
- JWT Authentication
- SQL Server & Stored Procedures

**DevOps & Project Management:**
- Azure DevOps
- Git (version control)
- Agile Development Methodology

---

## 👨‍💻 Responsibilities

- Designed and implemented database and entity models
- Developed generic repository base classes
- Created booking logic and occupancy tracking
- Built authentication with JWT and ASP.NET Identity
- Integrated Angular frontend with RESTful backend APIs
- Wrote and maintained unit and integration tests using Moq and xUnit
- Used Swagger for documenting APIs
- Designed UI/UX in Angular with Bootstrap

---

## 🚀 Getting Started

### Prerequisites

- [.NET SDK](https://dotnet.microsoft.com/download)
- [Node.js + npm](https://nodejs.org)
- [SQL Server](https://www.microsoft.com/en-us/sql-server)
- Angular CLI

### Setup Steps

1. Clone the repo:

```bash
git clone https://github.com/your-username/BookingApp.git
cd BookingApp
```

2. Set up the database:
   - Update connection string in `appsettings.json`
   - Run database migrations or SQL scripts manually

3. Run the backend:

```bash
cd BookingApp
dotnet run
```

4. Run the frontend:

```bash
cd BookingApp/ClientApp
npm install
ng serve
```

The app will be available at: `http://localhost:4200`

---

## 📦 Project Structure

```
BookingApp-DotNet-Angular-main/
├── BookingApp/                # Main ASP.NET Core project
│   ├── Controllers/
│   ├── Models/
│   ├── Data/
│   ├── Services/
│   └── ClientApp/             # Angular frontend
├── BookingAppTests/           # Unit tests
├── BookingAppIntegrationTests/
├── BookingApp.sln             # Solution file
└── README.md
```

---

## ✅ Testing

Run backend tests:

```bash
dotnet test
```

Run Angular tests:

```bash
cd BookingApp/ClientApp
ng test
```

---

## 📄 License

This project is licensed under the MIT License.

---

