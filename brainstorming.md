# Little Lemon App - Design Process

## Wireframes
### Home Screen Layout



## Component Breakdown
1. **Onboarding Screen**
   - First/Last Name text fields
   - Email field with validation
   - Profile image selector
   - Order status toggle

2. **Home Screen**
   - Header with logo
   - Hero section with promotional banner
   - Horizontal filter chips (Starters, Mains, Desserts, Drinks)
   - Menu items in vertical list with:
     - Dish image
     - Name
     - Price
     - Description

3. **Profile Screen**
   - Display saved user information
   - Edit mode with save/cancel buttons

## Data Flow
- User data persisted using CoreData/UserDefaults
- Menu items fetched from JSON/API
- State management for cart/orders
