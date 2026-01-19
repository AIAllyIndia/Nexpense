This screen allows you to enter all details needed to create a new expense entry and upload receipts.

##### **1. Expense Details**

- **Assign to Report** – Choose the report where this expense will be added.
    
- **Invoice ID (Optional)** – Helps prevent duplicate invoice submissions.
    
- **Invoice Date** – Select the date on the invoice.
    
- **Amount** – Enter the expense amount and currency.
    
- **Apply from Advance (Optional)** – Use available advance balance if applicable.
    
- **Category** – Select the appropriate expense category (Food, Travel, etc.).
    
- **Cost Centre / Project (Optional)** – Choose if your company uses them; selecting a project auto-fills its cost center.
    
- **Vendor / Expense Name** – Enter where the expense occurred (e.g., Starbucks).
    
- **Notes (Optional)** – Add any additional details.
    

##### **2. Receipt Upload**

- **Upload File(s)** – Attach receipts in image, PDF, or Excel format.
    
- **Take Photo** – Capture a receipt directly using the camera.
    

##### **3. Actions**

- **Create Expense** – Save and add the expense to your selected report.
    
- **Cancel** – Discard and go back.

![[nexpense_my_expense_create_1_v1.png]]

### **How AI Extracts Data From Your Receipt**

When you upload a receipt or invoice, NexPense uses **AI-powered OCR (Optical Character Recognition)** to automatically read and fill in your expense details.

##### **What the AI Extracts Automatically**

As soon as you upload a file or take a photo:

- **Invoice Number** – Read directly from the document.
    
- **Invoice Date** – Detected from printed dates on the receipt.
    
- **Amount** – Identifies the total amount, currency, and symbols like $, €, ₹, ¥, etc.
    
- **Vendor / Merchant Name** – Extracts the company name printed on the bill.
    
- **Currency Type** – Recognizes if the invoice is in USD, INR, EUR, etc.
    
- **Category Hints** – AI may suggest a category based on the vendor (e.g., food, office, travel).
    

All extracted fields are shown on the right side under **OCR Completed**.

##### **How Currency Conversion Works**

If the receipt is in a foreign currency:

- AI detects the **original currency** (e.g., USD).
    
- It applies the **latest exchange rate** automatically.
    
- Shows the **converted value** in your company’s base currency (e.g., INR).
    

This helps you submit expenses without manually calculating conversions.

##### **What You Can Edit**

Even though the system extracts everything automatically, you can still:

- Change the amount
    
- Correct the date or invoice number
    
- Update vendor name
    
- Choose a different category or cost centre
    
- Add additional notes
    

##### **Purpose**

This feature reduces manual entry and prevents mistakes by:

- Auto-reading receipts
    
- Avoiding duplicate entries
    
- Speeding up report creation
  
  
  ![[nexpense_my_expense_create_2_v1.png]]