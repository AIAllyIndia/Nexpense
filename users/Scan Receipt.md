User logs into the NexPense mobile application and lands on the dashboard.
User taps on the **“📷” icon** from the bottom navigation bar to start scanning a receipt.

![[docs/users/assets/nepense_dashboard_overview_1_v1.png]]

## 1. Screen Header & Navigation

At the top of the screen, the user sees:

![[nexpense_scan_reciept_header_1_v1.png|605]]

- **Screen Title** — _Scan Receipt_
    
- **Back Arrow** — Navigates to the previous screen
    
- **Help Icon (?)** — Provides guidance or help related to receipt scanning

This header ensures the user clearly understands they are in the receipt capture flow and can exit or seek help at any time.

## 2. Select Report Section

This section allows the user to decide where the expense should be saved.

![[nexpense_scan_reciept_select_report_v1.jpeg|405]]

- **Report Dropdown** — Default option:  
    _“Save to Expenses Only (Auto)”_
    
- Allows quick saving without attaching to a report

This reduces friction for users who want to upload receipts quickly and organize them later.

### 3. Receipt Upload

![[nexpense_scan_reciept_add_reciept1_v1.png|305]]

![[nexpense_scan_reciept_reciepts_1_v1.jpeg|505]]

- **Scan (Camera)** — Capture receipt using phone camera
    
- **Select Files** — Upload existing documents

Once a receipt is scanned or uploaded, OCR automatically starts extracting expense details.

## 4. Extracted Expense Details
After OCR processing, the system prepares expense fields for review.

![[nexpense_scan_reciept_expense_details_1_v1.png|305]]

### Key Fields Displayed:

- **Amount (₹)**
    
- **Date** (Auto-filled based on receipt)
User can verify and edit extracted values before proceeding.

The user is shown a structured form to complete expense details:
- **Vendor / Merchant**
    
- **Invoice ID / Receipt Number**
    
- **Category** (Dropdown with auto-suggestion)
    
- **Notes** (Optional)

## 6. Category Selection

![[nexpense_scan_reciept_category_1_v1.png|605]]

- Category is **auto-selected** (e.g., _Travel_)
    
- Dropdown allows manual change
    
- **Refresh icon** enables re-suggestion

Auto-classification saves time, while manual override ensures correctness.

## 7. Advance Balance Section

This section shows advance-related information:

![[nexpense_scan_reciept_balance_1_v1.png|605]]

- **Advance Balance (INR)**
    
- Available & total balance
    
- **Use Max** button
    
- Option to apply advance (if available)

## 8. Final Actions
At the bottom of the screen, the user can:

![[nexpense_scan_reciept_final_1_v1.png|605]]

- **Add to Report** — Saves the expense
    
- **Rescan** — Re-capture the receipt
    
- **Discard** — Cancel the process

## End-to-End Flow Summary

1. User opens **Scan Receipt**
    
2. Selects report option
    
3. Scans or uploads receipt
    
4. OCR extracts details
    
5. User reviews and edits data
    
6. Category and advance applied
    
7. Expense is added successfully

> Click here to see all the [[Expenses]]
> Click here to view [[docs/users/Reports|Reports]]