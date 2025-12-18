# Ethical Dilemma Simulator

An interactive web application built with ASP.NET Core Razor Pages that presents users with 10 real-life moral scenarios. Users make choices that affect their honesty and empathy scores, with results visualized using Google Charts API.

## 🎯 Overview

The Ethical Dilemma Simulator is an engaging web application that challenges users with ethical scenarios. Each choice impacts the user's moral alignment scores, which are calculated and displayed through an interactive pie chart visualization.

## ✨ Key Features

- **10 Real-Life Moral Scenarios**: Thought-provoking ethical dilemmas
- **Interactive Choice System**: Three choices per scenario affecting honesty and empathy scores
- **Score Calculation**: Dynamic calculation of moral alignment based on user choices
- **Data Visualization**: Google Charts API integration for visual score representation
- **Object-Oriented Design**: Clean architecture with encapsulated Player, Choice, and Scenario classes
- **Extensible Architecture**: Abstract base class for easy scenario type extension
- **Razor Pages UI**: Modern, responsive web interface

## 🛠️ Technologies Used

- **C#** - Core programming language
- **ASP.NET Core** - Web framework
- **Razor Pages** - Server-side page model
- **Google Charts API** - Data visualization
- **Object-Oriented Programming** - Encapsulation and inheritance
- **Bootstrap** - UI framework
- **jQuery** - JavaScript library

## 📋 Project Structure

```
DilemmaSimWeb/
├── Models/
│   ├── Player.cs          # Player model with Honesty and Empathy scores
│   ├── Choice.cs           # Choice model with score impacts
│   └── Scenario.cs         # Abstract Scenario base class
├── Pages/
│   ├── Index.cshtml        # Main page with scenarios
│   └── Shared/            # Layout and shared components
├── wwwroot/
│   ├── css/               # Stylesheets
│   └── js/                # JavaScript files
└── Program.cs             # Application entry point
```

## 🏗️ Architecture

### Object-Oriented Design

- **Player Class**: Tracks user's honesty and empathy scores
- **Choice Class**: Represents a choice option with score impacts and consequences
- **Scenario Class**: Abstract base class for ethical scenarios
- **EthicalScenario**: Concrete implementation of Scenario

### Key C# Concepts Demonstrated

- **Variables**: Static and dynamic variable allocation
- **Arithmetic Operations**: Runtime arithmetic evaluation for score calculation
- **Selection Statements**: Conditional logic for choice processing
- **Subprograms**: Modular code organization
- **Object-Oriented Programming**: Encapsulation, inheritance, and abstraction

## 🚀 Getting Started

### Prerequisites

- .NET SDK 6.0 or higher
- Visual Studio 2022 or Visual Studio Code (optional)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Nidhi0201/DilemmaSimWeb.git
cd DilemmaSimWeb
```

2. Restore dependencies:
```bash
dotnet restore
```

3. Build the project:
```bash
dotnet build
```

### Running the Application

1. Run the application:
```bash
dotnet run
```

2. Open your browser and navigate to:
```
https://localhost:5001
```
or
```
http://localhost:5000
```

## 📊 How It Works

1. **Scenario Presentation**: Users are presented with 10 ethical dilemmas
2. **Choice Selection**: For each scenario, users select from three choices
3. **Score Calculation**: Each choice affects the user's honesty and empathy scores
4. **Result Visualization**: After all scenarios, a Google Pie Chart displays the moral alignment

## 🎨 Features in Detail

### Scenario System
- Abstract base class allows for easy extension
- Each scenario contains multiple choices
- Choices have predefined score impacts

### Score Calculation
- Honesty score: Based on choices that reflect truthfulness
- Empathy score: Based on choices that reflect compassion
- Scores are calculated dynamically as users progress

### Visualization
- Google Charts API integration
- Interactive pie chart showing moral alignment
- Visual representation of honesty vs empathy balance

## 👤 Authors

**Nidhi Prajapati**
- GitHub: [@Nidhi0201](https://github.com/Nidhi0201)
- Portfolio: [Nidhi Prajapati Portfolio](https://github.com/Nidhi0201/Nidhi-Prajapati-Portfolio)

**Ujas Goti**
- Original repository: [Ujas-Goti/DilemmaSimWeb](https://github.com/Ujas-Goti/DilemmaSimWeb)

## 📄 Course Information

- **Subject**: CS 311
- **Professor**: Indirajyoti Yellapragada
- **Assignment**: Project Presentation

## 📄 License

This project was developed as part of CS 311 coursework. All rights reserved.

## 🙏 Acknowledgments

- Developed as part of CS 311 Software Engineering course
- Original repository: [Ujas-Goti/DilemmaSimWeb](https://github.com/Ujas-Goti/DilemmaSimWeb)
- Google Charts API for data visualization

---

**Note**: This is a forked repository from a group project. Contributions and improvements have been made to enhance functionality and code quality.
