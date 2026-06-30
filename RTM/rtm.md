# 📌 Requirements Traceability Matrix (RTM)

## Project Information

| Field | Details |
|--------|---------|
| **Project Name** | SauceDemo Manual Testing |
| **Application** | SauceDemo |
| **Application URL** | https://www.saucedemo.com |
| **Testing Type** | Manual Testing |
| **Prepared By** | Md. Naimur Rahman |

---

## Purpose

The Requirements Traceability Matrix (RTM) establishes the relationship between business requirements, test cases, execution status, and reported defects. It ensures that all critical requirements are covered by appropriate test cases and helps identify any gaps in testing.

---

## Requirements Traceability Matrix

| Requirement ID | Requirement | Module | Test Case ID | Test Scenario | Status | Bug ID | Remarks |
|----------------|------------|--------|--------------|---------------|--------|--------|---------|
| RQ-001 | User should be able to log in with valid credentials | Login | TC-001 | Valid Login | ✅ Pass | - | Login successful |
| RQ-002 | Locked users should not be able to log in | Login | TC-002 | Locked User Login | ✅ Pass | - | Proper error message displayed |
| RQ-003 | Products should be displayed correctly | Products | TC-003 | Verify Product Listing | ✅ Pass | - | Products loaded successfully |
| RQ-004 | Product images should match product details | Products | TC-004 | Verify Product Images | ❌ Fail | BUG-002 | Product image mismatch detected |
| RQ-005 | User should be able to add products to the cart | Cart | TC-005 | Add Product to Cart | ❌ Fail | BUG-003 | Add to Cart failed for affected products |
| RQ-006 | Shopping cart badge should update correctly | Cart | TC-006 | Verify Cart Badge | ✅ Pass | - | Cart count updated correctly |
| RQ-007 | Checkout should validate all mandatory fields | Checkout | TC-007 | Empty Checkout Validation | ❌ Fail | BUG-001 | Only First Name validation displayed |
| RQ-008 | User should complete checkout successfully | Checkout | TC-008 | Complete Checkout | ✅ Pass | - | Checkout completed successfully |
| RQ-009 | User should be able to logout successfully | Menu | TC-009 | Logout | ✅ Pass | - | Logout successful |

---

## Coverage Summary

| Metric | Count |
|--------|------:|
| Total Requirements | 9 |
| Covered Requirements | 9 |
| Coverage | 100% |
| Passed | 6 |
| Failed | 3 |

---

## Traceability Summary

- ✅ All identified requirements have corresponding test cases.
- ✅ All executed test cases have execution results.
- ✅ Failed test cases are linked to documented bug reports.
- ✅ The RTM confirms complete requirement-to-test coverage for this project.

---

## Related Documents

- 📄 Test Plan
- 📄 Test Cases
- 📄 Test Execution Report
- 📄 Test Summary Report
- 🐞 Bug Reports
- 📸 Screenshots

---

**Prepared By:** Md. Naimur Rahman  
**Repository:** SauceDemo Manual Testing