# Frontend Developer Challenge: Sales Data Dashboard 📊

## Overview

Welcome! In this challenge, you'll build a dashboard that displays sales data using React and TypeScript.

You may use any React setup and charting library you prefer. Choose tools that let you work most effectively!

## Time Expectation

- ~4 hours for core requirements
- Additional time for bonus features (optional)

## Core Requirements

### 1. Dashboard Display

Create a dashboard that shows:
- Key sales metrics
- Data visualizations (charts/graphs)
- Product performance data

### 2. Data Fetching

- Fetch data from the provided API endpoint
- Handle loading and error states
- Display the data appropriately

### 3. Visualizations

Include at least 2 different types of data visualizations using any charting library of your choice.

### 4. Documentation

- README with setup and run instructions
- Note which charting library you chose and why

## API Endpoint

```
GET https://api.jsonbin.io/v3/b/65b5f8b01f5677401f20d0cc
```

## Mock Data Structure

If you prefer to work with local data instead of the API, here's the complete mock data:

```typescript
const mockSalesData = {
  record: {
    salesData: {
      totalRevenue: 145670.50,
      totalOrders: 342,
      averageOrderValue: 425.35,
      topProducts: [
        { name: "Wireless Headphones", sales: 45000, units: 120 },
        { name: "Smart Watch", sales: 38000, units: 95 },
        { name: "Laptop Stand", sales: 22000, units: 220 },
        { name: "USB-C Hub", sales: 18500, units: 185 },
        { name: "Mechanical Keyboard", sales: 16000, units: 80 },
        { name: "Webcam HD", sales: 12000, units: 100 },
        { name: "Mouse Pad XXL", sales: 8500, units: 170 },
        { name: "Cable Organizer", sales: 6200, units: 310 }
      ],
      monthlySales: [
        { month: "Jan", revenue: 32000, orders: 75 },
        { month: "Feb", revenue: 28000, orders: 68 },
        { month: "Mar", revenue: 35000, orders: 82 },
        { month: "Apr", revenue: 41000, orders: 97 },
        { month: "May", revenue: 38500, orders: 91 },
        { month: "Jun", revenue: 44000, orders: 104 },
        { month: "Jul", revenue: 42000, orders: 99 },
        { month: "Aug", revenue: 39000, orders: 92 },
        { month: "Sep", revenue: 46000, orders: 108 },
        { month: "Oct", revenue: 48500, orders: 114 },
        { month: "Nov", revenue: 52000, orders: 122 },
        { month: "Dec", revenue: 58670.50, orders: 138 }
      ],
      salesByCategory: [
        { category: "Electronics", revenue: 95000, percentage: 65.2 },
        { category: "Accessories", revenue: 28500, percentage: 19.6 },
        { category: "Software", revenue: 12000, percentage: 8.2 },
        { category: "Services", revenue: 10170.50, percentage: 7.0 }
      ],
      recentOrders: [
        { id: "ORD-001", customer: "John Doe", amount: 299.99, status: "completed", date: "2024-01-16" },
        { id: "ORD-002", customer: "Jane Smith", amount: 549.50, status: "processing", date: "2024-01-16" },
        { id: "ORD-003", customer: "Bob Johnson", amount: 179.99, status: "completed", date: "2024-01-15" },
        { id: "ORD-004", customer: "Alice Brown", amount: 899.00, status: "shipped", date: "2024-01-15" },
        { id: "ORD-005", customer: "Charlie Wilson", amount: 125.75, status: "completed", date: "2024-01-14" }
      ],
      growthRate: 12.5,
      conversionRate: 3.8,
      customerSatisfaction: 4.6
    }
  }
};
```

## Bonus Features (Optional)

If you finish early, consider adding:
- Interactive features (filters, date ranges)
- Additional visualizations
- Export functionality
- Responsive design improvements
- Dark mode
- Real-time updates

## Submission Guidelines

### What We're Looking For

#### 🎯 Focus on These Core Areas:

1. **Working Dashboard**
   - Data displays correctly
   - Charts render properly
   - Clean layout

2. **Data Handling**
   - Proper API integration or data loading
   - Error handling
   - Data transformation as needed

3. **Code Quality**
   - Clean React/TypeScript code
   - Logical component structure
   - Good practices

#### 💡 Nice to Have:

- Beautiful visualizations
- Interactive features
- Performance optimizations
- Creative additions

## 📤 Submission

1. Create a new GitHub repository
2. Include setup instructions in your README
3. Deploy a demo if possible (optional)
4. Make the repository public
5. Send us the repository link

## ❓ Questions?

If something's unclear, make reasonable assumptions and document them in your README.

---

**Remember:** We want to see how you approach data visualization and API integration. Focus on creating a functional dashboard that clearly presents the data.

Good luck! 🚀