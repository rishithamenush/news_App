# News Application Using Clean Architecture 🗞️

This repository hosts the source code for a News Application built to demonstrate the principles of **Clean Architecture**. This project serves as a practical example of how to structure a Flutter application to achieve a clean separation of concerns, ensuring that the system is easy to maintain and extend over time.

## Project Overview 🌐

The **News Application** provides a dynamic platform to fetch, display, and manage news articles from various sources. By adhering to Clean Architecture, the app ensures that its business logic, user interface, data access, and external dependencies are cleanly separated, promoting scalability and testability.

## Why Clean Architecture? 🏛️

**Clean Architecture** is designed to organize code into distinct layers with specific roles, reducing dependencies on external frameworks or databases. This results in a more testable, scalable, and maintainable application. Here's how the Clean Architecture manifests in this project:

- **Entities Layer**: Contains core business models such as `NewsArticle` and `Category`.
- **Use Cases Layer**: Encapsulates all business rules like fetching and sorting news articles.
- **Interface Adapters Layer**: Converts data between the most convenient formats for use cases and entities to the format most convenient for external agencies like databases or web APIs.
- **Frameworks and Drivers Layer**: Includes frameworks like Flutter, along with databases and external APIs, keeping them isolated from business logic.

## Key Features 🔑

- **Fetch and display news articles** from various online sources.
- **User can filter and sort articles** based on categories or other parameters.
- **Designed to be both mobile and web-friendly** using Flutter.

## Getting Started 🚀

To clone and run this application, follow these steps:

```bash
git clone https://github.com/rishithamenush/news_App.git
cd news-application-clean-architecture
flutter pub get
flutter run
```
