# Project Summary
The Sales Mix Management System is a comprehensive web application designed for restaurants and food service businesses to efficiently manage their recipes, sales data, monthly reports, and inventory. The system provides features such as tracking ingredient quantities per unit sold, daily sales management, and variance calculations for inventory, along with the ability to import and export data in various formats.

# Project Module Description
- **Recipes (Sales Mix)**: Manage recipes with ingredient quantities and item details.
- **Daily Sales**: Input and track daily sales records.
- **Monthly Report**: Generate monthly reports with theoretical usage calculations.
- **Inventory & Movements**: Manage inventory levels and calculate variances.
- **Settings/Import**: Import data from Excel or JSON files and reset data.

# Directory Tree
```
.
├── index.html                    # Main HTML file for the Sales Mix Management System
├── sales-mix-system.html         # Alternate HTML file for the system (if applicable)
└── uploads/
    ├── clipboard (1).png         # Image file for recipe data
    └── clipboard.png              # Image file for recipe data
```

# File Description Inventory
- `index.html`: Contains the complete HTML structure and JavaScript for the Sales Mix Management System, including styles and functionality for managing recipes, sales, inventory, and reports.

# Technology Stack
- HTML5
- CSS3
- JavaScript
- LocalStorage for data persistence
- SheetJS library for Excel file handling

# Usage
1. **Installation**: No installation required; simply open the `index.html` file in a modern web browser.
2. **Dependencies**: The SheetJS library is included via CDN in the HTML file.
3. **Running the Application**: Open the `index.html` file to access the application. Data is saved automatically in the browser's LocalStorage.
