# 🐞 BUG-001: Checkout Validation Displays Only the First Required Field Error

## Bug Information

| Field | Value |
|--------|-------|
| **Bug ID** | BUG-001 |
| **Module** | Checkout |
| **Feature** | Checkout Information Validation |
| **Severity** | Medium |
| **Priority** | Medium |
| **Status** | Open |
| **Reported By** | Md. Naimur Rahman |
| **Environment** | Windows 11, Google Chrome (Latest), SauceDemo |

---

## Summary

When all required checkout fields are left empty and the **Continue** button is clicked, the application displays only the **"First Name is required"** validation message instead of indicating all missing required fields.

---

## Preconditions

- User is logged in as `standard_user`
- At least one product is added to the cart

---

## Steps to Reproduce

1. Login using a valid account.
2. Add any product to the cart.
3. Open the shopping cart.
4. Click **Checkout**.
5. Leave **First Name**, **Last Name**, and **Postal Code** empty.
6. Click **Continue**.

---

## Expected Result

The application should display validation messages for **all required fields** that are left empty.

---

## Actual Result

Only the **First Name is required** validation message is displayed.

---

## Reproducibility

Always (100%)

---

## Attachment

Refer to the relevant screenshot in the **Screenshots/Checkout** folder.