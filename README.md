# Excel_LOOKUPs

Master VLOOKUP() & XLOOKUP() for effortless data lookups! Sample Excel files + complete tutorials for sales data analysis and reporting.

## VLOOKUP Intro
**Syntax:** `=VLOOKUP(lookup_value, table_array, col_index_num, FALSE)`  
- Searches **first column only**, returns right-side value from same row  
- Exact match: `FALSE` parameter (e.g., customer name → product)  
- **Fix errors:** `=IFERROR(VLOOKUP(A2,$B$2:$G$13,3,FALSE),"Not Found")`

## XLOOKUP Intro (Excel 365)
**Syntax:** `=XLOOKUP(lookup_value, lookup_array, return_array, "Not Found")`  
- **Superior:** Bidirectional search (left/right columns work!)  
- Returns multiple columns: `=XLOOKUP(A2,IDs,B:D)`  
- Native error handling—no more #N/A wrapping needed

## 📖 Complete Guides
🎥 **VLOOKUP Tutorial:** [Step-by-Step Demo](https://youtu.be/0Vsyg-9YEJk)  
📄 **VLOOKUP Guide:** [How VLOOKUP Works](https://medium.com/@DatawithRose/636f1fa27c8b)  

🎥 **XLOOKUP Tutorial:** [Mastering XLOOKUP](https://youtu.be/ds1TPtwVFNA)  
📄 **XLOOKUP Guide:** [XLOOKUP Complete](https://medium.com/@DatawithRose/008f9da81228)  

## 🚀 Practice
1. Download repo files  
2. Open → Apply formulas from video timestamps  
3. **Result:** Clean matches across sales/customer datasets  

Let's [Connect](rosearmstrong.carrd.co)
