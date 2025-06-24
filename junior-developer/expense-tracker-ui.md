# Frontend Developer Challenge: Expense Tracker UI 💰

## Overview

Welcome! In this challenge, you'll build an expense tracking interface using React and TypeScript.

You may use any React approach you're comfortable with - Create React App, Vite, Next.js, or any other setup. Choose what lets you work most effectively!

## Time Expectation

- ~4 hours for core requirements
- Additional time for bonus features (optional)

## Core Requirements

### 1. Expense Management

Create an interface that allows users to:
- Add new expenses
- View all expenses
- Edit existing expenses
- Delete expenses
- See basic spending summaries

### 2. Expense Data Model

Each expense should include at least:
- Description
- Amount
- Category
- Date

Feel free to add other fields you think would be useful.

### 3. Categories

Support expense categories such as:
- Food & Dining
- Transportation
- Shopping
- Entertainment
- Bills & Utilities
- Other

### 4. Basic Features

- Form validation
- Currency formatting
- Date handling
- Basic calculations (totals, etc.)

### 5. Mock Data

Use the provided mock data below to populate initial expenses. No need to persist data between sessions.

### 6. Documentation

- README with setup and run instructions
- Basic usage guide

## Mock Data

```typescript
const mockExpenses = [
  {
    id: "1",
    description: "Grocery shopping at Whole Foods",
    amount: 125.50,
    category: "Food & Dining",
    date: "2024-01-15"
  },
  {
    id: "2",
    description: "Monthly subway pass",
    amount: 127.00,
    category: "Transportation",
    date: "2024-01-01"
  },
  {
    id: "3",
    description: "Winter jacket from REI",
    amount: 189.99,
    category: "Shopping",
    date: "2024-01-10"
  },
  {
    id: "4",
    description: "Electric bill",
    amount: 85.20,
    category: "Bills & Utilities",
    date: "2024-01-05"
  },
  {
    id: "5",
    description: "Coffee at Blue Bottle",
    amount: 5.75,
    category: "Food & Dining",
    date: "2024-01-16"
  },
  {
    id: "6",
    description: "Movie tickets",
    amount: 32.00,
    category: "Entertainment",
    date: "2024-01-13"
  },
  {
    id: "7",
    description: "Gas for car",
    amount: 45.00,
    category: "Transportation",
    date: "2024-01-14"
  },
  {
    id: "8",
    description: "Phone bill",
    amount: 65.00,
    category: "Bills & Utilities",
    date: "2024-01-08"
  },
  {
    id: "9",
    description: "Lunch with team",
    amount: 68.50,
    category: "Food & Dining",
    date: "2024-01-12"
  },
  {
    id: "10",
    description: "New headphones",
    amount: 149.99,
    category: "Shopping",
    date: "2024-01-07"
  }
];
```

## Bonus Features (Optional)

If you finish early, consider adding:
- Search or filter functionality
- Sort options
- Data visualization
- Export capability
- Monthly/weekly views
- Budget tracking

## Submission Guidelines

### What We're Looking For

#### 🎯 Focus on These Core Areas:

1. **Working Application**
   - Core CRUD operations function correctly
   - Clean user interface
   - Proper data handling

2. **React & TypeScript Usage**
   - Proper component structure
   - Appropriate use of hooks
   - TypeScript typing

3. **Code Quality**
   - Clean, readable code
   - Logical organization
   - Good practices

#### 💡 Nice to Have:

- Polished UI
- Additional features
- Performance optimizations
- Testing

## 📤 Submission

1. Create a new GitHub repository
2. Include setup instructions in your README
3. Deploy a demo if possible (optional)
4. Make the repository public
5. Send us the repository link

## ❓ Questions?

If something's unclear, make reasonable assumptions and document them in your README.

---

**Remember:** We're looking for clean, working code that demonstrates your React and TypeScript skills. Focus on delivering a functional solution.

Good luck! 🚀