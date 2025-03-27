# 📄 APBD_MVC_App

Prosta aplikacja webowa zbudowana w oparciu o wzorzec **ASP.NET Core MVC**, oparta na oficjalnym tutorialu Microsoft. Projekt został rozszerzony i dostosowany w ramach zajęć **APBD (Aplikacje Baz Danych)**.

## 📂 Struktura projektu

- `Controllers/` – kontrolery MVC odpowiedzialne za logikę aplikacji
- `Models/` – modele danych
- `Views/` – widoki Razor (.cshtml)
- `Data/`, `Migrations/` – konfiguracja Entity Framework (Code First)
- `appsettings.json` – konfiguracja połączenia z bazą danych
- `CW10.sln`, `CW10.csproj` – pliki projektu .NET

## ⚙️ Technologie

- ASP.NET Core MVC
- Entity Framework Core (Code First)
- Razor Pages
- SQL Server / LocalDB

## 🚀 Funkcjonalności

- CRUD dla podstawowych encji (np. Students, Courses itp.)
- Walidacja danych po stronie klienta i serwera
- Widoki oparte na layoutach Razor
- Migracje bazy danych z EF Core

## 📚 Jak uruchomić projekt

1. Otwórz projekt (`CW10.sln`) w Visual Studio 2022+
2. Przygotuj bazę danych:
```bash
dotnet ef database update
```
3. Uruchom projekt (F5 lub `dotnet run` w folderze głównym)

> 🔎 Upewnij się, że connection string w `appsettings.json` jest zgodny z Twoją lokalną instancją SQL Server.

## 👨‍💼 Autor
**Filip Michalski**  
Aplikacja stworzona w ramach kursu **APBD** jako ćwiczenie z architektury MVC oraz integracji .NET z bazami danych.
