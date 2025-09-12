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

# Card Navigation
- User clicks on **Card** icon from Home page and navigates to **Cards** page

<br/>

<img width="427" height="420" alt="image" src="https://github.com/user-attachments/assets/942930a4-d0a9-4ed1-94c3-9cec9fda0a6a" />
<br/>



- **Cards** page displays all saved cards  
- One card is tagged as **Primary**  
- The most recently added card is tagged as **Primary** by default  
- The **Primary** card is used by default during payment

<br/>

<img width="427" height="471" alt="image" src="https://github.com/user-attachments/assets/e662bcb7-a5f4-4aae-a917-18539fab4e88" />


<br/>


  # Card Details
- User can change `Primary` card  
- Clicking a card opens `Card Details` page. This page contains `card number`, `expiry date` and a `Set as Primary` toggle button to change the primary card.

<br/>

<img width="427" height="643" alt="image" src="https://github.com/user-attachments/assets/59751ca1-3a68-4b70-aeda-38516fc6e120" />

<br/>



  # Set primary card
- Enabling the toggle button shows popup`“Set as primary payment method”` with two button`yes` and `no` 
- Clicking `Yes` sets the selected card as `Primary`  
- Clicking `No` keeps the current `Primary` unchanged  


<br/>


<img width="427" height="329" alt="image" src="https://github.com/user-attachments/assets/489311bd-6618-4203-9487-293d57774892" />

<br/>



# Card Removal
- `Remove this card` button is displayed on **Card Details** page  
- Clicking this button shows a popup `“Remove this card?”` with two button `remove` and `cancel` 
- Clicking `Cancel` keeps user on **Card Details** page without changes  
- Clicking `Remove` deletes the card successfully

<br/>

  

<img width="414" height="582" alt="image" src="https://github.com/user-attachments/assets/4c99fde8-31d9-480f-a357-64cfae78c09f" />

<br/>



<img width="427" height="453" alt="image" src="https://github.com/user-attachments/assets/e90f22ef-155e-4885-bf33-346a63999e3a" />

<br/>


- **Primary** card cannot be removed and shows error message


  <br/>

<img width="427" height="519" alt="image" src="https://github.com/user-attachments/assets/5bc98163-aae1-4534-bae6-9215412c8538" />



<br/>


- Card with **pending transactions** cannot be removed and shows error message.


<br/>


<img width="427" height="551" alt="image" src="https://github.com/user-attachments/assets/d117e336-12f4-4930-9be8-3aae23673384" />

<br/>

# Card Addition
- User clicks `Add Card` button on **Cards** page

  
<br/>
<img width="427" height="464" alt="image" src="https://github.com/user-attachments/assets/90ef5aaa-8471-4d13-a5fa-39b52ea60481" />

<br/>


- `Add Card` page displays fields: `Cardholder Name`, `Card Number`, `Expiry Date`, `CVV`


<br/>

<img width="427" height="562" alt="image" src="https://github.com/user-attachments/assets/ab70e935-d15d-4314-b08b-acf02bf86191" />

<br/>


- Adding a card with valid details and successful **3DS** completion shows a success popup.


<br/>

<img width="379" height="414" alt="image" src="https://github.com/user-attachments/assets/9fa5e57d-5d7c-47db-96b3-01027e51059d" />

<br/>


- Adding a card with invalid/expired details shows error *“Invalid card details”*


<br/>

<img width="447" height="570" alt="image" src="https://github.com/user-attachments/assets/e544d8fc-ec18-4b5b-9c32-d749871452fd" />


<br/>

# Card Addition Failed
- Failed **3DS authentication** redirects to failure page with message  
- Failure page displays `Try Again` and `Try Later` options

<br/>

<img width="328" height="699" alt="image" src="https://github.com/user-attachments/assets/15f253e0-5780-48fc-9d71-8fa86ed2d8d5" />

<br/>

- Clicking`Try Again` redirects back to **Add Card** page  
- Clicking `Try Later` redirects back to **Cards** list page  

