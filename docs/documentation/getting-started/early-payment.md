---
title: Early Payment
deprecated: false
hidden: false
metadata:
  robots: index
---
# My Bills Page

The user goes to the `My Bills` page and finds the `Upcoming Payments` section with the next upcoming bill card, including `Merchant Name`, `Instalment Amount`, and `Due Date`. This section also contains a `view all` option. Users can tap `View All` to see all upcoming bills.

![](https://files.readme.io/efe598dacdc1f3592e9e33262e501ce229cd8f8a32ea71b14b21135c7773b66e-image.png)

# All Bills Page –> 'Upcomings' Tab

By clicking `view all`, user is redirected to the `All Bills` page and navigates to the `Upcomings` tab.

![](https://files.readme.io/02a922b6f4fe878c214ff66b9bf50e2016988753168d95d8460bcbb01bd1c139-image.png)

<br />

Use clicks on this card to see details. Each upcoming instalment `bill page` shows details of:

* `Transaction ID` -
* `Bill Amount` – Original bill total before discounts or fees
* `Discount` – Any voucher/promo code applied during 1st instalment
* `Billable Amount` – Final amount to be paid after discount
* `Processing Fee` – Service charge added during payment
* `Credit Shield Fee` – Optional fee for credit protection
* `Paid Amount` – Already paid portion of the bill
* `Due Amount` – Remaining balance for the current instalment
* `Timestamp` – Date and time of the instalment
* `Payment Method` – Indicates card used (e.g., Mastercard, Visa)

![](https://files.readme.io/c73d326ce639e0beb0eaec6aaea58d4a2b9a8a086af88053b40e21403e2589dd-image.png)

<br />

# Instalment Date Details with Amount

Current Instalment shows: `Instalment Amount`, `Processing Fee`,`Credit Shield Fee` and  ✅ Green Tick if already paid.

![](https://files.readme.io/f30f6646874206f5b0adbfcea39771dca167c83ab80c193df99b25408a4dbe30-image.png)

<br />

Upcoming Instalments (e.g., Plan 2, 3, 4) are shown with: 🔘 Gray Tick for unpaid instalments, Dates & Amounts per future schedule.

![](https://files.readme.io/74dbf5b8f155e0a09e19e0c318ac4c7c33c3879b3ee8454c448746440ea2f073-image.png)

# Payment History Section

Each payment plan is viewed in a card that contains: `Timestamp`,`Paid Amount`,`Card Number (last 4 digits)`,`Instalment Plan Number`,`Payment Status` – success / failed / pending

![](https://files.readme.io/36e90f8c316e13cb4982f286bc7bf1cf301c1a9b734717fdc39e62f5afe69181-image.png)

# Action Buttons

This page contains 2 action buttons.

<Image align="center" className="border" border={true} src="https://files.readme.io/531613d5e25030341209b55a9a6c977804d8d7877edb06df403e35b526464acb-image.png" />

BUTTON 1: `Switch Card`: Redirects to "Add Card" page to select another saved card or add a new card.

BUTTON 2: `Pay Earlier`: Triggers a popup modal with multiple buttons based on number of upcoming instalments.

![](https://files.readme.io/4c73a5525807e2ead69519b8ec646bb6fcd54babca4c2fafde644262ec119f8a-image.png)

<br />

Example:

If Plan 1 is paid and Plans 2 & 3 are pending:

Button 1: “Pay for 1 month” → Plan 2

Button 2: “Pay for 2 months” → Plan 2 + Plan 3

# Select Payment Method

By clicking any of the payment plan buttons, another pop-up modal appears. The modal contains buttons for each saved card. For example, `“Pay with XXXX-1234”``“Pay with XXXX-5678”` and `Use Other Option`.

![](https://files.readme.io/6b8b6af76eb0a6c189424b707f721481e6ba8dbd79635f84d118a7a157e30bfd-image.png)

`Use other option`button redirects to full checkout portal. Check-out Portal payment options Include:

* Online Banking (DuitNow)
* Debit/Credit Card
* E-wallets
* Moby BNPL
* Paylater with Credit Card

`(Refer to [Checkout Documentation] for complete payment method details)`

<br />

&#x20;