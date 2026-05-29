# Defect Report
- 4 defects found

---

## Defect Summary

| Severity  | Count | Open  | Closed |
| --------- | ----- | ----- | ------ |
| Critical  | 0     | 0     | 0      |
| High      | 2     | 2     | 0      |
| Medium    | 2     | 2     | 0      |
| Low       | 0     | 0     | 0      |
| **Total** | **4** | **4** | **0**  |

---

## Defect Log

### DEF-001: No Success Message When Updating Customer Information

| Field           | Details                                                               |
| --------------- | --------------------------------------------------------------------- |
| **Defect ID**   | DEF-001                                                               |
| **Related TC**  | TC_020                                                                |
| **Summary**     | Success message is not displayed after updating customer information |
| **Severity**    | Medium                                                                |
| **Priority**    | Medium                                                             |
| **Status**      | Open                                                                  |
| **Browser**     | Chrome                                                                |
| **Environment** | https://demowebshop.tricentis.com/                                    |

**Steps to Reproduce:**

1. Navigate to My Account → Customer info
2. Modify details
3. Click "Save button"

**Expected Result:**

- Customer information should be updated successfully
- A success confirmation message should be displayed to the user

**Actual Result:**

- Customer information is updated successfully
- No success confirmation message is displayed

---

### DEF-002: Buttons Are Missing

| Field           | Details                                                               |
| --------------- | --------------------------------------------------------------------- |
| **Defect ID**   | DEF-002                                                               |
| **Related TC**  | TC_027                                                                |
| **Summary**     | Responsive design issues on resize window                             |
| **Severity**    | Medium                                                                |
| **Priority**    | Medium                                                             |
| **Status**      | Open                                                                  |
| **Browser**     | Chrome                                                                |
| **Environment** | https://demowebshop.tricentis.com/                                    |

**Steps to Reproduce:**

1. Resize window

**Expected Result:**

- Layout adjusts according to screen size

**Actual Result:**

- Layout partially breaks on smaller window resize

### DEF-003: Buttons Are Missing

| Field           | Details                                                               |
| --------------- | --------------------------------------------------------------------- |
| **Defect ID**   | DEF-003                                                               |
| **Related TC**  | TC_029                                                                |
| **Summary**     | “Add to Cart” button missing in some product listing/card |
| **Severity**    | High                                                                |
| **Priority**    | High                                                             |
| **Status**      | Open                                                                  |
| **Browser**     | Chrome                                                                |
| **Environment** | https://demowebshop.tricentis.com/                                    |

**Steps to Reproduce:**

1. Navigate to a product category
2. heck for “Add to Cart” button on each product card

**Expected Result:**

- Add to Cart button display and clickable for all products

**Actual Result:**

- Some buttons are missing


### DEF-004: Buttons Are Missing

| Field           | Details                                                               |
| --------------- | --------------------------------------------------------------------- |
| **Defect ID**   | DEF-004                                                               |
| **Related TC**  | TC_030                                                                |
| **Summary**     | Currency type is missing from product prices                          |
| **Severity**    | High                                                                  |
| **Priority**    | High                                                                  |
| **Status**      | Open                                                                  |
| **Browser**     | Chrome                                                                |
| **Environment** | https://demowebshop.tricentis.com/                                    |

**Steps to Reproduce:**

1. Open website and observe the product price
   
**Expected Result:**

- Prices with a currency type and  two decimal places (Ex: $10.00)

**Actual Result:**

- Decimal format is correct but the currency type is missing


