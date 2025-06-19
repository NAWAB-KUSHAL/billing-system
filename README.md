# Author

- Nawab kushal 
- Bachelor of Computer Applications  
- Maulana Abul Kalam Azad University of Technology  
- Passionate about web development & healthcare applications.

# Contact

- Email: nawabkushal1@gmail.com  
- Phone: 8116587453

# Medical Billing System – MEDICINE CLINIC

This is a fully functional web-based Medical Billing System designed for small clinics or pharmacies like Small store , pharmacy management system or in local shop.

The application allows staff to manage customer details, generate bills, apply discounts, and store product metadata (like MRP, Expiry, Batch No., etc.).
It includes advanced features such as autocomplete, keyboard navigation, dynamic billing rows, and printable invoices.

# Features

- Customer Information Entry
  Capture name and phone number with keyboard navigation.

- Dynamic Billing Table 
  Add medicines/services with:
  - Quantity
  - Description (with autocomplete)
  - Pack, MFG, Batch No., Expiry
  - MRP, Discount, CGST, SGST
  - Auto-calculated Amount (after discount)
    Here the cgst and sgst was add in amount so, it don't calculate again when user gives input.
    
- Tax Display  
  Shows 6% CGST and 6% SGST for each item (only displayed, not included in total).

- Item Management Section  
  - Add new items (stored in browser local storage)
  - Search, view, and remove items
  - Item info auto-fills in billing table

- Keyboard Navigation
  - Enter key moves between fields
  - Arrow keys + Enter for selecting autocomplete options
  - Editable billing rows behave like Excel

- Resizable Item Modal
  - You can resize the "Add Item Info" modal using draggable corners.

- Real-time Clock
  - Displays current date and time in the header.

- Print-Friendly
  - Click "Print" to generate a clean invoice for printing.

# Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- LocalStorage (for item persistence)

# How to Use

1. Open the `index.html` file in a web browser.
2. Fill in Customer Name and Phone Number.
3. Enter data in the billing table:
   - Use autocomplete in the "Description" column.
   - Tab/Enter to move between fields.
4. Click Add Items to store new medicine info.
5. Add more rows with "Add Row" if needed.
6. Click Print to generate the invoice.


# Data Persistence

- Items added in the Item Modal are stored using LocalStorage.
- Data is retained even after the page reloads unless manually cleared.




