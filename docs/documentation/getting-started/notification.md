---
title: Overdue & Account Suspension
deprecated: false
hidden: false
metadata:
  robots: index
---
# Overdue Definition

An overdue payment occurs when a user fails to make a scheduled BNPL installment on the due date. Starting from the next day, the unpaid installment is considered overdue and may incur additional late fees.

# Account Suspension

A user’s BNPL account is suspended if they have one or more overdue bills. While suspended, the user:

* Cannot make any new BNPL transactions.
* Must clear all overdue bills (including late fees) to regain access.

Once the overdue bills are fully paid, the account will be unsuspended, and the user can use BNPL services again.

# Suspension Notification & User Journey

## Step 1: Suspension Notification

After login, the user will find a notification about account suspension in the app’s notification section.

<Image align="left" src="https://files.readme.io/5ab992e2183e3c0160fcd3a140e059bedcdfd66790b4a471900f04ae799a1da0-image.png" />

<Image align="center" src="https://files.readme.io/55e3b9b26ae3ce15d299adf49f571fbab54ba2f8c29c472f666a8a50f906f388-image.png" />

## Step 2: Suspended Account Alert

On the home screen, a card is displayed:

* Message: `Account temporarily suspended`
* Shows overdue amount
* Includes a button: `Pay to Activate`

![](https://files.readme.io/fe0c980323ce9cd6a04d0b10bddbcb22f8aa82b2f9e6a4d10e9bf50742ecd512-image.png)

<br />

## Step 3: Pay to Activate

When the user clicks `Pay to Activate`, they are redirected to the Due Bills page (if multiple overdue bills exist).

## Step 4: Due Bills Page

The Due Bills page displays a list of overdue and upcoming installments.

Each list item shows:

* Due amount
* Installment status indicator
* `Pay Now` button

![](https://files.readme.io/05d0b6ce676ba534afd3885967f7c0c39e5a2258ff36995c6ae10ae63dcee72e-image.png)

<br />

### Indicator Guide:

* 🟢 Green → Successful installment
* 🔴 Red → Overdue installment
* ⚪ Grey → Upcoming installment

## Step 5: Single Due Bill Case

If the user has only one overdue bill, clicking “Pay to Activate” will redirect them directly to the payment page, skipping the “Due Bills” page.

## Step 6: Payment Completion

After successful payment, the user will receive:

* A payment success `notification` (including late fee details).
* An unsuspension `notification` once all due bills are cleared.

![](https://files.readme.io/b86bdc905115990b66a04022127e2f290ef7d5c172c39ed56e88a97e2e1f5d62-image.png)

## Step 7: Account Reactivation

After being unsuspended:

* The user can again make BNPL transactions.
* The home screen will show the spending limit balance instead of the suspended account alert card.

<Image align="center" width="160px" src="https://files.readme.io/cf81149303573e7d29cb10b5c6be5b6095c239ff6bfb7c331acaa40c38845d90-image.png" />

<br />
