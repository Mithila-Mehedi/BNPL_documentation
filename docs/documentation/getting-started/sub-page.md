---
title: BNPL Payment Flow
deprecated: false
hidden: false
metadata:
  robots: index
---
# Scan Merchant QR

The user starts by clicking the Scan icon on the home screen to launch the QR scanner.

**`Scan Icon`**: An icon on the home screen to open the camera and scan QR codes.

**`Merchant QR`**: A unique code displayed by a merchant to receive payments.

<Image align="center" width="35% " src="https://files.readme.io/a2142b5372e6d2b14a5a5a9479b99aa43da347588075999aedc5be8819c7b952-a021af3b-212b-42b3-a898-bfe6ed85c5d4.jfif" />

<br />

# Enter Payment Amount

After scanning, the user is directed to a screen with a text input field. They enter the amount they wish to pay. The Next button remains disabled until an amount is typed. Once entered, the button becomes active.

`Payment Amount Field`: A text box where the user types how much they want to pay.

`Next `Button: The button to move to the next screen, becomes active after entering a valid amount.

<Image align="center" width="250px" src="https://files.readme.io/ac36d008560541bde8e358b61991f6063646ab8b1d48dc8cf396c9834ab8851c-image.png" />

<br />

# Bill Details Page

Clicking "Next" takes the user to the Bill Details page. This screen summarizes the bill and allows the user to choose payment frequency and installment options.

`Merchant Name`: The business receiving the payment.

`Bill Amount`: The amount the user entered on the previous screen.

`Voucher/ Promo Code`: Optional discount that can be selected from an available voucher list.

`Select` Functionality: Allows users to choose a promo code from a list.

<Image align="center" src="https://files.readme.io/8bcc7a56cd4d366885048b601cd94d71390dd4459764ceb6c635bfda7fa2b51b-Screenshot_111.png" />

<br />

# Choose Payment Frequency

The user selects how often they want to make payments — either biweekly or monthly. This is a required selection.

`Biweekly`: Payment made every two weeks.

`Monthly`: Payment made once a month.

![](https://files.readme.io/61eab5855390b116dcd0d6877238fbd717342a97002ac5b9c80d6c50b80fa321-image.png)

<br />

# Select Payment Option

The user now chooses a payment plan, such as `Pay Now`, `Pay in 2`, `Pay in 3`, or `Pay in 4`. These plans split the payment and show all cost details.

`Pay Now`: Pay the full amount immediately.

`Pay in 2/3/4`: Divide the amount over multiple payments with added fees.

`Installment Plan Info`: Breakdown of how much to pay now, future installments, and fees.

![](https://files.readme.io/2ccee88d394aa6ce1309056d08772f8e3ac72066fed31086e2629f180d68a628-image.png)

<br />

`Pay in 2`: The total payment amount entered by the user (e.g., RM 140.00).

`Pay Today`: The portion of the bill charged immediately, including any upfront fees.

`Instalment`: A part of the total payment that is scheduled to be paid on a future date. (e.g., RM 125.00 on 7 Jul 2025).

`Processing Fee`: An extra service fee charged for using the instalment plan.

`Credit Shield Fee`: Optional fee for protection against missed payments (if any).

`Discount`: Any promotional or voucher-based amount reduced from the total.

# Choose or Switch Card

User sees the card saved during eKYC. They can either use this card or tap `Switch` to add a new one.

![](https://files.readme.io/bf726d644bc26f4f1224e3fe5f8614bba1c93b4fc47e8d65cbbbd4dc14b42b84-image.png)

<Image align="center" src="https://files.readme.io/8a3593c5bfe905088a609d5152c71b0f1f11a3d913b217f8cb70f7820708b1ae-image.png" />

<br />

`Saved Card`: A card previously added and stored securely.

`eKYC`: A process to verify identity of a customer.

`Switch` Button: Takes the user to the “Add Card” page.

`Add Card Page`: A screen to switch cards or save a new card for payment.

# Tap “Pay Now”

After confirming the plan and card, the user taps the “Pay Now” button to start the final payment step.

`Pay Now` Button: Confirms the selected payment option and proceeds to final approval.

![](https://files.readme.io/ad03d1bd20c6a675719cb46d469c0e38a62b6a9c909b91110927ea64ae2c55b4-image.png)

<br />

# Spend Responsibility Popup

A modal appears explaining the consequences of late payment and the fee that will apply. The user must agree to continue.

![](https://files.readme.io/65ee590f4af0169ecdd72732c6bff1e4ad237e4a196f6d5f6d4ab66dc3de4130-image.png)

<br />

`Spend Responsibility Modal`: A popup message showing late payment policy.

`Cancel Button`: Go back without paying.

`Late Payment Fee`: Extra charge if the user misses a payment deadline.

`“I Understand, Proceed to Pay” button`: Accepts the terms and continues.

# Authentication via Passcode

The user is prompted to enter their passcode. If the passcode is correct, the system processes the payment.

`Passcode`: A secure code set by the user to authorize transactions.

![](https://files.readme.io/0206b21213ce9efe2f294c4f0b975ccfc033247f54a053070c48bf3be8f3c513-image.png)

<br />

# Payment Successful Page

After successful authentication, the user is shown a confirmation page with full payment details.

![](https://files.readme.io/b8c9ce63cb1aa4c895c1c2d09c790fcb5b7e8140bc4e3a90b3d0eaa410d27b77-image.png)

<br />

`Paid Amount`: What was charged now.

`Transaction ID`: Unique identifier of the payment.

`Timestamp:` Date and time of payment.

`Payment Method`: Card or source used.

`Installment Plan Detail`: Breakdown of today’s and future payments.

`Done` Button: Finishes the flow and redirects to the `my bill` page.

# Redirect to My Bills

User taps the Done button to go to the My Bills page, where they can view upcoming and recent payments.

![](https://files.readme.io/df58314626c0185019fe9f1b598c53293de34a219f509ab009c9ef041c2b5bbb-image.png)