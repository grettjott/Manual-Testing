# DEFECTS REGISTRATION EXAMPLES

# Title 1: Visual banner information is hidden

## 1. Description:
Button is hidden by another visual element.

## 2. Steps to Reproduce:
1. Navigate to big-box.lt page.
2. Locate the button [Sutinku su...] in the bottom right corner of the page.
3. Observe the positioning of the button.
4. Notice that another element overlaps or hides the button, making it inaccessible or difficult to see.

## 3. Expected Result:
The button should be clearly visible without being obstructed by other elements on the page.

## 4. Actual Result:
The button is hidden or partially covered by another element, which makes it difficult or impossible to interact with.

## 5. Environment:
* Browser: Chrome Version 128.0.6613.84
* Operating System: Windows 10

## 6. Screenshots/Recordings:
![b1](https://github.com/user-attachments/assets/ef771a01-28b7-4b33-be0d-d4c955e846bd)

# Title 2: Only one error message is displayed, even though all fields are not filled

## 1. Description:
The form only displays a single error message, even though multiple fields are left unfilled.

## 2. Steps to Reproduce:
1. Navigate to big-box.lt/prisijungimas page.
2. Click [REGISTRUOTIS]
3. Leave all fields empty (name, email, etc.).
4. Click the submit button [REGISTRUOTIS]

## 3. Expected Result:
Each unfilled field should display an individual error message, indicating which specific fields need to be completed and filled.

## 4. Actual Result:
Only one error message is shown, even though there are multiple empty fields in the form.

## 5. Environment:
* Browser: Chrome Version 128.0.6613.84
* Operating System: Windows 10

## 6. Screenshots/Recordings:
![b2](https://github.com/user-attachments/assets/ef974c41-65ed-48d7-bcf4-6e296df40c44)

# Title 3: Wishlist selection as 'default' does not work

## 1. Description:
If two wishlists are created and second, named '2' are marked as default, products are still added to the first wishlist named '1'.

## 2. Steps to Reproduce:
1. Log in to the account with valid credentials.
2. Create two wishlists. '1', '2'.
2. Mark second wishlists named '2' as default. [Numatytasis]
3. Add a product to the wishlist.

## 3. Expected Result:
The products should be added only to default wishlist.

## 4. Actual Result:
Wishlist selection as 'default' does not work, products are still added to the first wishlist named '1'.

## 5. Environment:
* Browser: Chrome Version 128.0.6613.84
* Operating System: Windows 10

## 6. Screenshots/Recordings:
![b3](https://github.com/user-attachments/assets/a2d0cf8d-7682-4c6e-ae3d-d5e1100ab230)

