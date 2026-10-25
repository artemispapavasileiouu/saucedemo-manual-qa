BUG-001: Unexpected Product Name Reference in Sauce Labs Backpack Description

Related Test Case: TC-007 — Verify Products Page  
Severity: Low (provisional)  
Priority: Medium (provisional)  
Environment: SauceDemo web application  
Preconditions: The user is logged in as `standard_user` and is on the Products page.

Steps to Reproduce:
1. Log in to https://www.saucedemo.com/ using valid credentials.
2. Locate the Sauce Labs Backpack product.
3. Read the product description.

Expected Result:
The product description should contain the intended, accurate product information, consistent with the applicable product content requirements.

Actual Result:
The product description begins with the expression `carry.allTheThings()` instead of explicitly referencing the product name, Sauce Labs Backpack, as expected by the tester.

Status: New


BUG-002: Unexpected Text in T-Shirt Product Title

Related Test Case:** TC-007 — Verify Products Page  
Severity: Low (provisional)  
Priority: Medium (provisional)  
Environment: SauceDemo web application  
Preconditions: The user is logged in as `standard_user` and is on the Products page.

Steps to Reproduce:
1. Log in to https://www.saucedemo.com/ using valid credentials.
2. Locate the red T-shirt product.
3. Read the product title.

Expected Result:
The product title should display the intended product name according to the applicable product content requirements.

Actual Result:
The product title is displayed as `Test.allTheThings() T-Shirt (Red)`. The prefix `Test.allTheThings()` appears before the product name.

Status: New

