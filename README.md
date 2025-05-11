# TypeScript Vehicle Builder

## Description

This command-line application allows users to create and interact with different types of vehicles including cars, trucks, and motorbikes. Built with TypeScript and the Inquirer package, it demonstrates object-oriented programming principles such as inheritance, interfaces, and polymorphism.

The application lets users:

- Create new vehicles with custom specifications
- Select existing vehicles from an inventory
- Perform various actions with vehicles (start, accelerate, turn, etc.)
- Execute vehicle-specific actions (trucks can tow, motorbikes can do wheelies)

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Walkthrough Video](#walkthrough-video)
- [Technologies Used](#technologies-used)
- [License](#license)

## Installation

To install this application, follow these steps:

1. Clone the repository:
   git clone https://github.com/jadenszewczak/vehicle-builder.git
2. Navigate to the project directory:
   cd vehicle-builder
3. Install dependencies:
   npm install

## Usage

To run the application:
npm start

Follow the prompts to create new vehicles or select existing ones, then choose actions to perform.

## Features

- **Object-Oriented Structure**: Utilizes TypeScript classes, inheritance, and interfaces
- **Vehicle Types**:
  - **Car**: Four-wheeled vehicle with basic driving capabilities
  - **Truck**: Four-wheeled vehicle with towing capabilities
  - **Motorbike**: Two-wheeled vehicle that can perform wheelies
- **Interactive CLI**: User-friendly command-line interface using Inquirer.js
- **Extensible Design**: Easily add new vehicle types or actions by extending base classes

## Walkthrough Video

[Click here to view the walkthrough video](https://youtu.be/-ng2kkreCoQ)

## Technologies Used

- TypeScript
- Node.js
- Inquirer.js
- Object-Oriented Programming principles
- Command-Line Interface (CLI) design

## License

This project is licensed under the MIT License.
