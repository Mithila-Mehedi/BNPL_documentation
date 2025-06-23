---
title: BNPL Payment Flow
deprecated: false
hidden: false
metadata:
  robots: index
---
**`Scan Merchant QR`**

The user starts by clicking the Scan icon on the home screen to launch the QR scanner.

**Scan Icon**: A button on the home screen to open the camera and scan QR codes.

**Merchant QR**: A unique code displayed by a merchant to receive payments.

Enter Payment Amount

After scanning, the user is directed to a screen with a text input field. They enter the amount they wish to pay. The Next button remains disabled until an amount is typed. Once entered, the button becomes active.

Payment Amount Field: A text box where the user types how much they want to pay.

Placeholder: Greyed-out hint text saying "Payment Amount".

Next Button: A button to move to the next screen, becomes active after entering a valid amount.

Bill Details Page

Clicking "Next" takes the user to the Bill Details page. This screen summarizes the bill and allows the user to choose payment frequency and installment options.

Merchant Name: The business receiving the payment.

Bill Amount: The amount the user entered on the previous screen.

Voucher / Promo Code: Optional discount that can be selected from a dropdown.

Select Functionality: Allows users to choose a promo code from a list.

Choose Payment Frequency

The user selects how often they want to make payments — either biweekly or monthly. This is a required selection.

Biweekly: Payment made every two weeks.

Monthly: Payment made once a month.

Radio Button: A circle the user clicks to choose one option from a group.

Step 5: Select Payment Option\
Explanation:
The user now chooses a payment plan, such as "Pay Now", "Pay in 2", "Pay in 3", or "Pay in 4". These plans split the payment and show all cost details.

Definition:

Pay Now: Pay the full amount immediately.

Pay in 2/3/4: Divide the amount over multiple payments with added fees.

Payment Option: Different ways to structure the payment.

Instalment Plan Info: Breakdown of how much to pay now, future instalments, and fees.

Example (Pay in 2):

Input Bill Amount: RM 150.00

Pay Today: RM 86.00

Next Instalment: RM 75.00 due on 7 Jul 2025

Processing Fee: RM 11.00

Credit Shield Fee: RM 0.00

Discount: RM 0.00

Step 6: Choose or Switch Card\
Explanation:
User sees the card saved during eKYC. They can either use this card or tap "Switch" to add a new one.

Definition:

Saved Card: A card previously added and stored securely.

eKYC: Electronic Know Your Customer – a process to verify identity.

Switch Button: Takes the user to the “Add Card” page.

Add Card Page: A screen to enter and save a new card for payment.

Step 7: Tap “Pay Now”\
Explanation:
After confirming the plan and card, the user taps the “Pay Now” button to start the final payment step.

Definition:

Pay Now Button: Confirms the selected payment option and proceeds to final approval.

Step 8: Spend Responsibility Popup\
Explanation:
A modal appears explaining the consequences of late payment and the fee that will apply. The user must agree to continue.

Definition:

Spend Responsibility Modal: A popup message showing late payment policy.

Late Payment Fee: Extra charge if the user misses a payment deadline.

Cancel Button: Go back without paying.

“I Understand, Proceed to Pay”: Accepts the terms and continues.

Step 9: Authentication via Passcode\
Explanation:
The user is prompted to enter their passcode. If the passcode is correct, the system processes the payment.

Definition:

Passcode: A secure code set by the user to authorize transactions.

Authentication: Verifying user identity before completing the action.

Step 10: Payment Successful Page\
Explanation:
After successful authentication, the user is shown a confirmation page with full payment details.

Definition:

Paid Amount: What was charged now.

Transaction ID: Unique identifier of the payment.

Timestamp: Date and time of payment.

Payment Method: Card or source used.

Instalment Plan Detail: Breakdown of today’s and future payments.

Step 11: Redirect to My Bills\
Explanation:
User taps the Done button to go to the My Bills page, where they can view upcoming and recent payments.

Definition:

Done Button: Finishes the flow and goes to the next page.

My Bills Page: A list view of both future and past payments.