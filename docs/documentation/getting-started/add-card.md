---
title: Add Card
deprecated: false
hidden: false
metadata:
  robots: index
---

# Card Management

This document outlines the test scenarios and validations for the Card Management flow, including navigation, card details, card removal, and card addition.

---

## Card Navigation
- User clicks on **Card** icon from Home page and navigates to **Cards** page

<img width="368" height="420" alt="image" src="https://github.com/user-attachments/assets/942930a4-d0a9-4ed1-94c3-9cec9fda0a6a" />


- **Cards** page displays all saved cards  
- One card is tagged as **Primary**  
- The most recently added card is tagged as **Primary** by default  
- The **Primary** card is used by default during payment

<img width="520" height="471" alt="image" src="https://github.com/user-attachments/assets/e662bcb7-a5f4-4aae-a917-18539fab4e88" />

---

  ## Card Details
- User can change `Primary` card  
- Clicking a card opens `Card Details` page. This page contains `card number`, `expiry date` and a `Set as Primary` toggle button to change the primary card.

<img width="438" height="643" alt="image" src="https://github.com/user-attachments/assets/59751ca1-3a68-4b70-aeda-38516fc6e120" />

---

  ## Set primary card
- Enabling the toggle button shows popup`“Set as primary payment method”` with two button`yes` and `no` 
- Clicking `Yes` sets the selected card as `Primary`  
- Clicking `No` keeps the current `Primary` unchanged  


<img width="451" height="329" alt="image" src="https://github.com/user-attachments/assets/489311bd-6618-4203-9487-293d57774892" />


---

## Card Removal
- `Remove this card` button is displayed on **Card Details** page  
- Clicking this button shows a popup `“Remove this card?”` with two button `remove` and `cancel` 
- Clicking `Cancel` keeps user on **Card Details** page without changes  
- Clicking `Remove` deletes the card successfully
  

<img width="314" height="582" alt="image" src="https://github.com/user-attachments/assets/4c99fde8-31d9-480f-a357-64cfae78c09f" />



<img width="429" height="453" alt="image" src="https://github.com/user-attachments/assets/e90f22ef-155e-4885-bf33-346a63999e3a" />


- **Primary** card cannot be removed and shows error message
  

<img width="504" height="519" alt="image" src="https://github.com/user-attachments/assets/5bc98163-aae1-4534-bae6-9215412c8538" />



- Card with **pending transactions** cannot be removed and shows error message


<img width="535" height="551" alt="image" src="https://github.com/user-attachments/assets/d117e336-12f4-4930-9be8-3aae23673384" />



---

## Card Addition
- User clicks **Add Card** button on **Cards** page  
- **Add Card** page displays fields: *Cardholder Name, Card Number, Expiry Date, CVV*  
- Adding a card with valid details and successful **3DS** completion shows a success popup  
- Adding a card with invalid/expired details shows error *“Invalid card details”*  

---

## Card Addition Failed
- Failed **3DS authentication** redirects to failure page with message  
- Failure page displays **Try Again** and **Try Later** options  
- Clicking **Try Again** redirects back to **Add Card** page  
- Clicking **Try Later** redirects back to **Cards** list page  

