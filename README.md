# Little Lemon 🍋

A food ordering app that allows users to browse Little Lemon's menu and place orders.

## Preview
![App Demonstration](https://user-images.githubusercontent.com/93353925/227747468-3e923704-873f-4a06-8bbb-8fad77580034.gif)

## Features
- [✅] **Onboarding Screen** - Collects user's personal details on first launch
- [✅] **Stack Navigation** - Back button support between screens
- [✅] **Home Screen** with:
  - App header
  - Promotional hero section
  - Menu category breakdown
  - Scrollable food menu list
- [✅] **Profile Screen** - Displays and edits user information
- [✅] **Data Persistence** - Saves profile changes between app sessions

## Screen Archetypes & Navigation Flow
```mermaid
graph TD;
    A[Onboarding] -->|First Launch| B[Home];
    B --> C[Menu Details];
    B --> D[Profile];
    D -->|Save| B;
