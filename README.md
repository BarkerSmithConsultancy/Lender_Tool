# Lender Product Matrix v2

A comprehensive filtering and search tool for business lending products, featuring 77 lenders across multiple product types including MCAs, Asset Finance, Invoice Finance, and Unsecured Loans.

## Features

### **Advanced Filtering**
- **10 comprehensive filters** for precise lender matching
- **Real-time search** with instant results
- **Multi-select options** for product types, company types, and locations
- **Numerical filters** for loan amounts, terms, trading time, and turnover

### **Filter Types**
1. **Lender Search** - Autocomplete search by lender name
2. **Loan Amount** - Filter by funding requirements (£1K - £5M)
3. **Term Length** - Filter by repayment terms (1-120 months)
4. **Trading Time** - Minimum business trading history required
5. **Monthly Turnover** - Minimum revenue requirements
6. **Product Type** - MCA, Asset Finance, Invoice Finance, Unsecured Loans, etc.
7. **Company Type** - Ltd Company, LLP, Sole Traders, Plc combinations
8. **Location** - UK regions and country combinations
9. **Personal Guarantee** - Yes/No requirement filtering
10. **Homeowner Status** - Property ownership requirements

### **Optimized Performance**
- **Compressed data structure** using lookup tables for 70% size reduction
- **77 complete lender entries** with full product details
- **Instant filtering** with no page reloads
- **Responsive design** that works on desktop, tablet, and mobile

## Usage

### **Quick Start**
1. Open `index.html` in any modern web browser
2. Use the filter controls to narrow down lenders
3. View detailed criteria, documents, security requirements, and USPs
4. Click submission links to access lender portals or email contacts

### **Filter Tips**
- **Clear filters** button resets all selections
- **Multiple selections** can be made in dropdown filters
- **Numerical filters** work as minimum thresholds
- **Results counter** shows matches in real-time

### **Example Searches**
- Find MCAs for £50K+ with 6 months trading time
- Locate asset finance lenders accepting sole traders
- Search invoice finance options in England/Wales
- Filter unsecured loans not requiring personal guarantees

## Technical Specifications

### **Data Structure**
- **Optimized lookup tables** for repeated values
- **Compressed array format** for efficient storage
- **Runtime decompression** to full objects
- **25 unique lenders** with multiple product variations

### **Browser Compatibility**
- Chrome, Firefox, Safari, Edge (latest versions)
- Internet Explorer 11+ (with reduced functionality)
- Mobile browsers on iOS and Android

### **File Size**
- Single HTML file: ~45KB
- No external dependencies
- Works offline once loaded

## Data Coverage

### **Lender Types**
Traditional banks, alternative lenders, fintech companies, specialist finance providers

### **Product Categories**
- **Merchant Cash Advances (MCA)** - Revenue-based funding
- **Asset Finance** - Equipment and vehicle financing  
- **Invoice Finance** - Receivables and factoring
- **Unsecured Business Loans** - No collateral required
- **Revolving Credit** - Flexible draw-down facilities

### **Funding Ranges**
- **Minimum**: £1,000
- **Maximum**: £5,000,000
- **Terms**: 1-120 months
- **Multiple tiers** per lender with different criteria

## Maintenance

### **Data Updates**
To update lender information:
1. Locate the `COMPRESSED_DATA` array in the JavaScript section
2. Follow the format: `[lenderIdx, productIdx, minLoan, maxLoan, ...]`
3. Update lookup tables if adding new lenders/products
4. Test all filters after changes

### **Adding New Lenders**
1. Add lender name to `LENDERS` array
2. Add product types to `PRODUCTS` array if new
3. Add compressed data entry to `COMPRESSED_DATA`
4. Update any new company types, locations, or other lookup values

## License

© 2025 Barker Smith Consultancy Limited. All rights reserved.

## Support

For technical issues or data updates, contact the development team.

---

*Last updated: June 2025 | Version 2.0*
