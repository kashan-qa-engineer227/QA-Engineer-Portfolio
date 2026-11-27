
# Test Execution Report

## 1. Project Information

| Field | Details |
|---|---|
| Project | Practice Software Testing |
| Testing Type | Manual Functional Testing |
| Website | https://practicesoftwaretesting.com/ |
| Tester | QA Portfolio Project |
| Status | Execution Completed for Tested Scenarios |

## 2. Testing Objectives

The objective was to verify the functionality of the login system, product listing, product details, and shopping cart.

## 3. Test Execution Summary

| Module | Test Cases Executed | Passed | Blocked / Clarification |
|---|---:|---:|---:|
| Login Functionality | 5 | 5 | 0 |
| Product & Cart | 5 | 4 | 1 |
| **Total** | **10** | **9** | **1** |

## 4. Login Testing Results

| Test Scenario | Expected Result | Actual Result | Status |
|---|---|---|---|
| Valid login credentials | User logs in successfully | Login successful | PASS |
| Invalid password | Error message displayed | Invalid email or password | PASS |
| Empty email and password | Required field errors displayed | Both required errors displayed | PASS |
| Invalid email format | Validation error displayed | Email format is invalid | PASS |
| Empty email with password entered | Email validation displayed | Email is required | PASS |

## 5. Product & Cart Testing Results

| Test Scenario | Expected Result | Actual Result | Status |
|---|---|---|---|
| Product listing | Products, images, names and prices visible | Information displayed correctly | PASS |
| Search existing product | Matching product displayed | Search bar not found | REQUIRES CLARIFICATION |
| Search feature availability | Search feature accessible | No search bar or icon found | BLOCKED |
| Product details | Product information displayed | Details and purchase options visible | PASS |
| Add product to cart | Product added successfully | Confirmation and correct product details displayed | PASS |

## 6. Observations

- Login validation messages worked as expected.
- Product listings displayed relevant information.
- Product details page opened successfully.
- Adding products to the cart worked correctly.
- A search feature could not be located and requires clarification against the application requirements.

## 7. Conclusion

The tested login, product listing, product details, and cart scenarios produced successful results.

The search-related scenario requires further clarification because no search interface was found during testing.

This report documents the results of a beginner-level manual testing project.

---
**End of Report**
