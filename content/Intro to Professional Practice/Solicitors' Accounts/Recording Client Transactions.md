---
aliases: 
tags: 
date created: Monday, August 22nd 2022, 10:08:05 am
date modified: Sunday, December 10th 2023, 12:39:50 am
pandoc-latex-admonition:
# order is important
  - color: firebrick
    classes: [admonition, admonition-danger]	
  - color: blue
    classes: [admonition, admonition-note]
  - color: green
    classes: [admonition, admonition-statute]
  - color: aquamarine
    classes: [admonition, admonition-action]
  - color: orange
    classes: [admonition, admonition-warning]
  - color: blue
    classes: [admonition, admonition-note]
  - color: yellow
    classes: [admonition, admonition-defn]
  - color: darkred
    classes: [admonition, admonition-guid]
  - color: pink
    classes: [admonition, admonition-test]
  - color: cyan
    classes: [admonition, admonition-tip, admonition-important]
  - color: purple
    classes: [admonition, admonition-example]
  - color: gray
    classes: [admonition]
---

# Recording Client Transactions

```toc
```

Records of client money dealings must be clearly separated from the records of the ordinary business dealings of a firm.

## Format

Books must be:

- Maintained on the double-entry principle
- Legible, up-to-date and contain narratives alongside entries which provide adequate information about a transaction.
- Ledger accounts should include the name of the client and a description
- Business counts in relation to each client must be kept up-to-date
- Inter-ledger transfers separately recorded.

### Dual Cash Account

Normal to have two individual cash accounts displayed next to one another, and two separate ledger accounts displayed together (though usually these are combined into one big ledger).

## Receipts of Money

- Receipts of client money held for the relevant client in the client bank account
- Receipts of business money will reduce the indebtedness of the relevant client to the firm.

## Payments of Money

- Decide which account the payment is being made from.
- Record CR entry on cash account.
- DR entry on the ledger account of the client on whose behalf the payment is being made.

## Firm's Professional Charges

A bill to clients will include professional charges and VAT on these charges. Accounts should show:

- Client owes the firm for charges and VAT.
- Firm has earned income in the form of professional charges and owes HMRC VAT.

The bill should include details of disbursements already paid on the client's behalf and disbursements to be paid in the future.

No entries are made on the accounts in relation to disbursements when the bill is sent.

Recall r 8.1: all inter-account transfers must be recorded on the client account ledger.

## Cash Transfers

May occur on:

- Payment of a firm's professional fees and disbursements
	- Once a bill or other written notification has been issued.
- To advance money where the solicitor needs to make a payment on behalf of the client/ trust where there is insufficient client money available.
- To replace money withdrawn in breach of r 5.3 (withdrawn client money where insufficient funds held to make the payment).
- To allow the client a sum in lieu of interest.

## Client → Business Bank Account

1. Record the payment of money from the client bank account
	1. CR cash account
	2. DR client's ledger account
2. Record the receipt of money into the business bank account.
	1. DR cash account
	2. CR client's ledger account.

## Inter-client Transfers

A 'paper' or 'inter-client' transfer is when the money held in the client bank account recorded as being held for client A, is changed to be recorded as held for client B.

### Recording

- DR client ledger account of first client
- CR client ledger account of second client.

## Split Cheques, Mixed Receipts and Bills

### Split Cheques

If you receive a cheque made up partly of business money and partly of client money, may be possible to “split” the cheque (if allowed by the bank).

- Business portion to cash account – DR business section
- Client portion to cash account – DR client section
- Business portion to client ledger – CR business section
	- Client portion to client ledger – CR client section.

### Unsplit Cheques and Direct Transfers

When a mixed receipt is received, the firm can choose whether to pay it initially into the client or business bank account. Money must be transferred 'promptly' to the correct account (14 days was specified under the old rules).

When clients pay by bank transfer, it is usual to give the client details of a client bank account, and then make transfers as necessary to the business bank account.

Entries:

- DR whole amount to cash account (client section)
- CR whole amount to client ledger (client section)

When later transferring business portion

- CR cash account (client section)
- DR client ledger (client section)
- DR cash account (business section)
- CR client ledger (business section).

## Dealing with Bills

- Payments for professional charges/ disbursements will be the firm's own money and must be paid into the business bank account.
- Where the firm is holding client money and money is due to the firm for disbursements paid with the firm's own money, money cannot be transferred unless a bill has been issued, or the firm made it clear that money would be used this way.
- Money received for a paid disbursement is the firm's money, not client money
- Billing for unpaid disbursements can cause risks to client money.

## Receipt of Cheque Made Out to the client/ TP

If you receive a cheque made out to the client, you cannot pay the cheque into a firm bank account. The only obligation is to forward the cheque to the payee without delay. The cheque is not client money, just paper. Many firms have a policy of recording where all cheques are received, irrespective of the payee.

## Dishonouring Cheques

There is nothing preventing a firm drawing against a cheque which has been paid into the client bank account but which has not yet been cleared. But if the cheque is dishonoured, there will be a breach of r 5.3 (only withdrawing from client account if $\exists$ sufficient funds).

Any breaches of rules must be corrected promptly on discovery (r 6.1).

## Abatements

A firm may decide to abate the costs to the client (e.g., if the client complains). To record the abatement, reverse the entries made on the profit costs and HMRC account when the bill was sent (to the extent of the abatement). Also send the client a VAT credit note.

- DR profit costs account
- DR HMRC account
- CR client ledger account (business section).

If preferred, the firm may debit abatements to a separate abatements account.

## Bad Debts

If a client is not going to pay the amount it owes to a firm, the firm will have to write off the amount owing for:

- Professional charges
- VAT
- Disbursements paid from the business bank account.

| VAT treatment | Description                                                                    |
| ------------- | ------------------------------------------------------------------------------ |
| General rule | There is no VAT relief; VAT must be accounted for even if debt is written off |
| Exception     | Where the debt has been outstanding for at least 6 months since the date payment was due, solicitor is entitled to a refund from HMRC.                                                                                |

So generally, for the whole amount:

- CR client ledger, business section
- DR bad debts account

And under the exception, when VAT relief becomes available, add:

- CR bad debts account VAT
- DR HMRC VAT

## Petty Cash

When cash is withdrawn from the bank for petty cash

- CR cash, business section
- DR petty cash account.

If a payment is made for a client using petty cash, an election has been made to use business money for the transaction.

## Insurance Commission

A law firm may be offered commission from insurance companies/ financial services companies. But it is rare for a firm to be entitled to keep this commission.

> [!statute] SRA Code for Firms, r 5.1
> You properly account to clients for any financial benefit you receive as a result of their instructions, except where they have agreed otherwise.

"Properly account for" means

- Paying to the client
- Offsetting against fees
- Keeping only when the client has been informed and agreed

Firms that wish to take advantage of the exemption allowing professional firms to avoid regulation by the Financial Reporting Council in relation to investment business must account for all commission to clients.
