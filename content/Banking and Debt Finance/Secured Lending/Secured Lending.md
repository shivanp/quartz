---
aliases: 
tags: 
date created: Friday, December 2nd 2022, 9:17:41 am
date modified: Sunday, December 10th 2023, 12:41:42 am
pandoc-latex-admonition:
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
  - color: yellow
    classes: [admonition, admonition-defn]
  - color: darkred
    classes: [admonition, admonition-guid]
  - color: pink
    classes: [admonition, admonition-test]
  - color: cyan
    classes: [admonition, admonition-tip]
  - color: cyan
    classes: [admonition, admonition-important]
  - color: purple
    classes: [admonition, admonition-example]
  - color: darksalmon
    classes: [admonition, admonition-conduct]
  - color: gray
    classes: [admonition]
---

```toc
min_depth: 0
```

# Common Securities

## Categorising Security

Different types of loan security have different effects:

- Security which gives the bank rights over an asset
- Security under which ownership in the secured asset is transferred to the bank
- Security under which a bank has actual (or "constructive") possession of the secured asset.

```ad-defn
title: Ownership
Having (legal or equitable) title to an asset.
```

```ad-defn
title: Possession
Having physical possession of an asset.
```

## Giving Rights Over Assets

Charges may be ‘fixed’ or ‘floating’ and are always ‘equitable’ (other than the ‘charge by deed expressed to be by way of legal mortgage’ (LPA 1925, s 87) which is arguably not a true ‘charge’ anyway).

## Fixed Charges

- The most certain way to ensure a secured asset is available to meet unpaid monies is to take possession of it (a “pledge”).
	- Prevents the borrower disposing of the asset or diminishing its value.
	- Impractical or impossible for a bank to take possession of certain assets (e.g., machinery)
- A fixed charge (“specific equitable charge”) gives the bank rights over an asset which:
	- prohibit the borrower from disposing of the asset without permission;  
	- attempt to maintain the asset’s value whilst it is in the borrower’s hands; and  
	- allow the bank recourse to the asset in the event of the borrower’s default under the loan.

This allows the borrower to use the charged assets unless and until any “enforcement event” occurs.

On an ‘enforcement event’, under its contractual rights in the charge document, the bank may require the borrower to sell the asset, or the bank may take possession of, and sell, the asset, or appoint a receiver to do the same (this carries less risk for the bank since the receiver acts as the borrower’s agent).

```ad-tip
If the borrower sells an asset subject to a fixed charge, the rights created by the charge usually remain with the asset.
```

## Floating Charges

A fixed charge is still unsuitable to secure assets which a borrower might want to deal with quickly at an unspecified future date (e.g., stock). Most companies are unable to grant fixed charges for the majority of their assets. With a floating charge, whatever assets in a particular class that a borrower owns at any point in time are subject to the floating charge.

- A floating charge secures a group of assets, which may fluctuate from time to time.
- The assets secured by a floating charge are identified generically, for example a borrower’s ‘trading stock’ or its ‘undertaking and assets’.
- Unlike a fixed charge, a floating charge specifically allows the borrower to deal with the charged assets in the **ordinary course of business** (construed widely).
- Possible to create more than one floating charge over the same group of assets.

```ad-defn
In [[Re Yorkshire Woolcombers Association [1904] AC 355]], a floating charge was defined as

- A class of assets, present and future; and
- Which in the ordinary course of the company's business changes from time to time; and
- It is contemplated that until the holders of the charge take steps to enforce it, the company may carry on business in the ordinary way as far as concerns the assets charged.
```

Subsequent cases have emphasised the third characteristic identified by Romer LJ. Thus, if a charge allows a borrower to deal with the charged assets without the bank’s consent, it almost certainly will not be a fixed charge. Similarly, if a borrower is not free to deal with secured assets without the bank’s consent, the security will be fixed even if it is described as ‘floating’ in the security document ([[Russell Cooke Trust Company Ltd v Elliott [2007] EWHC 1443 (Ch)]]).

### Crystallisation

When a floating charge crystallises, it ceases to float over all the assets in a class and instead fixes onto the assets in the class charged at the time of crystallisation. The lender then has control of these assets, and the borrower is unable to deal with them, as if the assets were subject to a fixed charge.

However, the assets subject to crystallisation of the floating charge are **not** treated as fixed charge assets for distribution purposes on a winding up.

If the company receives more assets of the same class after crystallisation, these are automatically subject to the crystallisation charge ([[NW Robbie and Co v Whitney Warehouse Co Ltd [1963] 1 WLR 1324, CA]]). The triggering events for crystallisation are set out in contract.

```ad-note
title: Partial crystallisation
Most charges provide for crystallisation to be simultaneously effective over all the assets secured by the charge. There is, however, no reason why a floating charge should not be partially crystallised.
```

- Advantages
	- Allows the company to deal with the secured assets on a day-to-day basis.
	- Allows the company to maximise the amount they are able to borrow.
	- Charge may be granted over the whole of the company's business.
- Disadvantages
	- On crystallisation, a floating charge ranks behind any fixed security created before it crystallised and is subject to any 3rd-party rights, including legal or equitable rights, which accrue prior to crystallisation.
	- Prior to crystallisation, the company could sell existing stock and not purchase new stock to replace it, if there is just a floating charge over stock.
	- Preferential creditors also take priority over the holder of a floating charge (e.g., employees, pension payments ([[Bloom and others v Pensions Regulator (Nortel, Re) [2010] EWHC 3010 (Ch)]]), ring-fenced amount for the unsecured creditors).
	- Under s 245 IA 1986, in certain circumstances a floating charge is automatically void and a liquidator/ administrator can set it aside (basically if created at the 'relevant time' where it was obvious the company would fail).
		- In Re Comet Group Limited, the judge described its purpose as “to prevent a company that is on its last legs from creating a floating charge to secure past debts or to secure moneys which do not go to swell its assets and become available for creditors”.
	- Crystallising a floating charge will create an effective stranglehold on a borrower: without the use of its current assets it cannot usually make any money.

Crystallisation occurs:

1. In common law
2. Specified event—as defined in the loan agreement. This usually occurs where a borrower defaults on the loan repayments or interest payments, or where another lender enforces their security.

#### Under Common Law

Events causing a floating charge to crystallise from case law:

- The borrower's liquidation
	- All types of winding-up, including a voluntary winding-up
	- But not just a petition for winding up being presented
- Appointment of a receiver/ administrative receiver by the bank
	- If the purpose of the administrative order is to prevent the borrower from continuing to run the business as a going concern
	- Mere crystallisation of another floating charge will not cause crystallisation under common law.
- Borrower ceasing to carry on business
- Intervention by the bank.

#### Under the Charge Document

Circumstances precipitating crystallisation commonly agreed contractually between the borrower and bank in the charge document:

- An immediate right to crystallise the floating charge upon giving notice to the borrower.
	- Borrower may add “if the bank reasonably believes the secured assets are in jeopardy”
- $\exists$ specified events which crystallise the charge without any action by the bank - "automatic crystallisation"
	- e.g., appointment of an administrator.

#### Post-crystallisation

```ad-important
A floating charge creates an immediate security interest but does not attach to any individual asset until crystallisation. 
```

Crystallisation does not in itself create a new charge to be registered under the CA 2006 ([[Re Manurewa Transport Ltd [1971] NZLR 909]]).

#### Weaknesses of Floating Charges

- Later fixed charges
	- Vulnerable to later fixed charges (unless there is a prohibition on creating further security)
- Administrator's costs
	- Floating charges rank behind administrator costs and expenses.
	- All liquidation expenses (other than litigation expenses) have automatic priority over floating charge holders, and are recoverable from the assets of the company
- Preferential creditors
	- Any proceeds realised from assets secured by a floating charge must be used to pay any ‘preferential debts’ of the company before meeting claims under the floating charge (IA 1986, s 40).
		- ‘Preferential debts’ are defined as including (s 386 & Sch 6 IA 1986) outstanding employees' wages and pension scheme contributions.
		- Prescribed part fund for unsecured creditors; 50% of the first £10,000 of the prescribed part and 20% thereafter, subject to a maximum amount of £800,000 if created on or after 6 April 2020 (£600,000 if created before) (see IA 1986, s 176A).
- Avoidance of floating charges.
	- Liquidator/ administrator can apply to court to have a floating charge set aside (s 245);
		- If granted to a connected person within 2 years of the onset of insolvency, or
		- If granted to an unconnected person within 12 months of the onset of insolvency.
	- Not invalid in either case to the extent that it is in return for valuable consideration given on or after the creation of the charge.

## Transfer of Ownership

### Mortgages

The security provider retains possession of the asset, but transfers ownership to the creditor. Security taken by transferring ownership (i.e., legal or equitable title) to the bank, along with a right to sell on default and an obligation to re-transfer title on satisfaction of the debt. Highest form of security.

Subject to the security provider's right to require the creditor to transfer the asset back to it when the debt is repaid. Right is known is the '[[equity of redemption]]'. The equity of redemption is held in reserve and only exercised if the borrowed money is not repaid.

A type of mortgage (known as “charge by way of legal mortgage” or “charge by deed expressed to be by way of legal mortgage”–s 87 LPA 1925) is usually taken over land. Ownership will remain vested in the security provider in this case.

```ad-tip
A mortgage can therefore be thought of as an ‘enhanced’ charge, since it gives rights over an asset which are backed with a transfer of legal or equitable title.
$$\text{Mortgage} = \text{Right of appropriation} + \text{Transfer of ownership}$$
```

Subject to contrary intention (and statutory restrictions in the case of land), a (legal) mortgage entitles the bank to take immediate possession of the mortgaged asset. But taking possession is not required to perfect the security.

#### Mortgage Over Land

The only way to create legal security over freehold or leasehold land is by way of ‘a charge by deed expressed to be by way of legal mortgage’ (LPA 1925, s 87). The net result is to provide the bank with rights equivalent to granting it a 3,000-year lease (or, for leasehold, a lease for one day less than the borrower’s lease).

#### Equitable Mortgages

If a mortgage does not transfer legal title, it will be an equitable mortgage. These can be created by:

- Written agreement by a borrower that the property is secured by equitable mortgage
- Agreement to provide a legal mortgage if the borrower intended the agreement to have immediate legal effect.
- Mortgage over an equitable interest
	- Where the borrower holds an equitable interest in the land (i.e., they are not a legal owner, e.g., a beneficiary in a trust of land), any mortgage of that interest will be equitable in nature.
	- Such a mortgage can be created very informally. In accordance with [s 53(1)(c) LPA 1925](https://www.legislation.gov.uk/ukpga/Geo5/15-16/20/section/53), such a mortgage need only be in writing and signed by the grantor in order to be validly created.
- Purported legal mortgage that does not comply with the necessary formalities.
	- A mortgage over registered land which is not granted by a valid deed or that is not completed by registration will not take effect as a legal mortgage (it will be defective).
	- However, it may be regarded as an equitable mortgage if it complies with [s 2 LP(MP)A 1989](https://www.legislation.gov.uk/ukpga/1989/34/section/2). Equity will recognise it as a ‘contract to grant a legal mortgage’ providing it is in writing, contains all the agreed terms and is signed by both the mortgagor and mortgagee.

There is little practical difference between an equitable mortgage and equitable fixed charge.

##### Disadvantages of Equitable Mortgages

```ad-warning
An equitable mortgage can be ignored by a bona fide purchaser (or ‘security taker’) for value of the legal title to an asset without notice (actual or constructive) of the equitable security.
```

But this disadvantage is largely overcome if the equitable security is registered since this provides notice of the security to anyone searching the register.

An equitable mortgage may not benefit from the ‘automatic’ powers vested in legal mortgagees under LPA 1925, s 101, which include the power of sale (although these powers should be specifically given in the security document).

## Giving Physical Possession

### Pledge

```ad-defn
A pledge is a way of creating security by the actual (or constructive) delivery of a tangible movable asset to a creditor, to be held until the performance of an obligation (eg, repaying a debt). The bank will take possession while the borrower retains ownership.
```

There is a right to sell the asset to settle the debt owed, upon the giving of reasonable notice.

#### Pledgee Rights

The security is the possession of an asset. A pledged asset must be “delivered” by the borrower. This can be through physical delivery or “constructive delivery” i.e., vesting control (e.g., keys to a safe deposit box).

```ad-note
title: Delivery of documents
Assets may be pledged by delivery of documents, if these documents effectively provide control. So holding the share certificate of a registered share does not give sufficient control, even if accompanied by a blank stock transfer form. 
```

The pledge ends when the pledged asset is returned to the borrower. The most important right implied by a pledge is the right to sell pledged assets to meet a defaulted debt.

#### Problems

A bank will probably want to take a pledge only over valuable assets - how can these be kept secure? The bank will probably be liable as bailee while it holds the pledged assets, and this may entail insurance costs.

No legal requirement to document a pledge, but documentation is a good idea (“letter of pledge” / “memorandum of deposit”).

#### Pledge-able Assets

- Asset must be capable of actual/ constructive delivery.
- Common to pledge bearer instruments (e.g., bills of exchange, bearer bonds).

### Lien

The right to physical possession of the debtor's goods until the debt is paid. But no right to sell these assets to settle the debt owed. Liens arise automatically under English law in certain types of commercial relationship.

3 types:

1. Common law/ particular liens
	- Allows retention of the goods under which the debt arises (e.g., a dry-cleaner retaining cleaned suits until paid).
2. Statutory/ general liens
	- Statutory liens allow certain persons to retain any goods in their possession against any obligation owed to them by the owner of those goods.
	- Arise by operation of law without any agreement
	- e.g., stockbrokers, solicitors, innkeepers benefit.
3. Equitable liens
	- Lien does not require possession of the property to which it attaches (usually land) and will give a right of sale through application to the court.
	- Also possible for a lien to be created by a contract.

Common law and statutory liens are both types of legal lien. Legal liens will usually require actual possession of the property which has been rightfully acquired. Generally no right to sell the property, with the exception of a banker's lien.

## Assignment

An assignment may be used to create a mortgage over certain assets.

The most common assets secured by assignment are a borrower’s rights against a third party (‘choses in action’), for example debts, and rights under various contracts.

An assignment by way of security can be legal or equitable:

- Legal if s 136 LPA 1925 complied with (“statutory assignment”) - notice in writing.
	- Written notice alone will not necessarily be sufficient to make an assignment legal as opposed to equitable. For example, an assignment of part will always be equitable even if notice is given.
- Equitable “assignment by way of charge”.

Assignment ‘by way of charge’ is expressly excluded from s 136 and so assigning rights by way of security will constitute a legal assignment only if it is an absolute assignment with a proviso for re-assignment on satisfaction of the secured obligation.

```ad-statute
title: 136 - Legal assignments of things in action.

(1) Any absolute assignment by writing under the hand of the assignor (not purporting to be by way of charge only) of any debt or other legal thing in action, of which **express notice in writing** has been given to the debtor, trustee or other person from whom the assignor would have been entitled to claim such debt or thing in action, is effectual in law (subject to equities having priority over the right of the assignee) to pass and transfer from the date of such notice—
- (a) the legal right to such debt or thing in action;
- (b) all legal and other remedies for the same; and
- (c) the power to give a good discharge for the same without the concurrence of the assignor:

Provided that, if the debtor, trustee or other person liable in respect of such debt or thing in action has notice—
- (a) that the assignment is disputed by the assignor or any person claiming under him; or
- (b) of any other opposing or conflicting claims to such debt or thing in action;he may, if he thinks fit, either call upon the persons making claim thereto to interplead concerning the same, or pay the debt or other thing in action into court under the provisions of the M1Trustee Act, 1925.
```

Assignments by way of security will always include a provision (either explicit or implied) for reassignment on satisfaction of the debt. Priority between assignments depends on notice being given to the third party.

```ad-warning
It is not possible to take a legal assignment over future choses in action. So an assignment can never cover e.g., future debts. 
```

## Terminology

- Debenture
	- At common law, any document which a company issues to acknowledge, or create, a debt.
	- In banking, the document under which a borrower creates the security for a secured loan, usually incorporating fixed and floating charges along with other security interests.
- Charge
	- Appropriation of assets to the satisfaction of a debt (creating an equitable security interest)
	- Generic label for most securities
- Security
	- Refers to the provision of rights against a person’s assets which are intended to enhance the probability of recovering a debt claim against them.
	- In banking, refers to the instrument (piece of paper) on which the borrower acknowledges the debt etc.
- Statutory definitions
	- In the LPA 1925, ‘mortgage’ is defined to include ‘any charge or lien on any property for securing money or money’s worth’.
	- Under the IA 1986, ‘security’ means ‘any mortgage, charge, lien or other security’ (s 248(b)).
	- In the CA 2006, the term ‘charge’ includes a ‘mortgage’.

## Key Features

| Type of Security | Key feature                                                                                                                             |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| Charge           | The beneficiary takes rights over the asset.                                                                                            |
| Pledge           | The beneficiary takes possession over the asset.                                                                                        |
| Mortgage         | The beneficiary takes title to the asset or, alternatively (in the case of land), rights equivalent to those enjoyed by a title holder. |
| Common law lien  | The beneficiary retains possession of the asset.                                                                                                                                         |

# Quasi-Security

There are various ways a bank might choose to enhance its prospects of repayment, which are not strictly security interests because they are not “rights in rem”.

## Guarantees and Comfort Letters

```ad-defn
title: Obligors
The borrower, together with any third parties willing to support the borrower's repayment obligations. 
```

Guarantors are also known as sureties.

### Guarantees

- A guarantee is a form of undertaking by one party to answer for another party's liabilities, usually on default.
- A guarantor will frequently be a company in the same group as the borrower.
- The company which has given the guarantee may be required to give security over its own assets.
- A parent company usually also guarantees punctual performance of the borrower's obligations.

### Guarantees Vs Indemnities

A guarantee creates a contractual ‘secondary’ obligation, which relies on there being a valid primary obligation between two parties other than the guarantor. The guarantor's obligation is contingent on the primary obligation. It will therefore never be greater than that of the obligor under the underlying agreement.

An indemnity creates an obligation to indemnify a party for a specified loss which it may incur. Unlike a guarantee, an indemnity creates a ‘stand alone’ (or primary) obligation which is independent of the liability or default of another party. It is independent of, and not contingent on, the obligations of the primary obligor. This means that, if the underlying transaction is set aside for any reason, the indemnity will remain valid.

It is possible for both a guarantee and an indemnity to be given at the same time. For the lender, it is essential that a guarantee of a loan is supported by an indemnity if the lender is to be properly protected.

```ad-action
When including both an indemnity and a guarantee in the same document, it is very important to spell out the terms of the obligations, as the onus will be on the lender to prove that the document is both a primary and secondary obligation. The title of the document will not determine whether it is a guarantee or an indemnity, or both, and neither will the practice of referring to a guarantor and indemnifier simply as a guarantor, even though this is widespread.
```

Assume that A has borrowed money from B, and so A owes a contractual obligation to repay that money to B.

> A guarantee is a promise by a party to ensure that another party carries out its obligations, or a promise to fulfil those obligations itself if the other party does not do so.

> An indemnity is a promise to reimburse someone in the event that they suffer a stated loss.

Suppose C indemnifies B against non-repayment of the loan to A. Then C's obligation is a primary obligation, so C's liability might ultimately be even more than A's was. Provides greater protection for B: it can look to either A or C for payment.

| Guarantee                                                                                                                                                                                                                                                   | Indemnity                                                                                                                                                                                                   |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Must be in writing or evidenced in writing and signed by the guarantor or its agent (s 4 Statute of Frauds)                                                                                                                                                 | No formal requirements for a valid indemnity                                                                                                                                                                |
| Constitutes a secondary liability                                                                                                                                                                                                                           | Constitutes a primary liability                                                                                                                                                                             |
| Secondary nature of the liability under a guarantee means if the underlying transaction is set aside for any reason/ underlying obligor discharged from liability, the guarantors obligations under the guarantee will also be unenforceable or discharged. | Primary nature of the liability under an indemnity means if the underlying transaction is set aside for any reason or the underlying obligor is discharged from liability, the indemnity will remain valid. |
| Guarantor only liable to the beneficiary to the same extent as the obligor is liable to the beneficiary                                                                                                                                                     | Indemnifier liable to the beneficiary independently of the obligor, and its liability may exceed the obligor's liability.                                                                                   |
| Variation of guaranteed obligations may discharge the guarantee.                                                                                                                                                                                            | Variation of underlying obligations will not generally discharge the indemnity.                                                                                                                             |
| Beneficiary can claim against the guarantor after the principle obligor defaults in its obligations.                                                                                                                                                        | The beneficiary can claim against the indemnifier irrespective of a default by the principal obligor.                                                                                                                                                                                                             |

### Indemnity Advantages

- Primary obligation is more robust than a secondary obligation since it is not dependent on the underlying obligation.
- Guarantee requires formalities (in writing and signed by the guarantor or a person authorised by it)
- Guarantees vulnerable if any changes made to the underlying obligation.
	- _[Holme v Brunskill (1878) 3 QBD 495](https://uk.westlaw.com/Document/IC2F31920E42711DA8FC2A0F0355337E9/View/FullText.html)_ established the rule that any amendments of the primary underlying contract, after the giving of the guarantee, will discharge the guarantor's liability under the guarantee unless either:
		- The guarantor consents to the variation.
		- The variation is patently insubstantial or incapable of adversely affecting the guarantor.
	- Above rule does not apply to indemnities (_[GPP Big Field LLP v Solar EPC Solutions SL [2018] EWHC 2866 (Comm)](https://uk.westlaw.com/D-102-7705?originationContext=document&transitionType=PLDocumentLink&contextData=%28sc.Default%29&comp=pluk)_)

### Practical Implications

- Substance not form is important
- If A's obligations cease, then if C has provided a guarantee, C's obligation under the guarantee will also cease, because it is dependent on A's obligation
- If C provides an indemnity, this would remain in place.
- If there is a change to the contract between A and B after the guarantee/ indemnity is given, then a guarantee would almost always be discharged, but an indemnity would remain in force.
- To execute a guarantee, it must be in writing and signed by the guarantor. Not necessary for an indemnity.

### Legal Implications

1. Since the guarantee creates a ‘secondary’ obligation, the guarantor will not be liable unless the borrower’s debt becomes due.
	1. Most banks will therefore require that the ‘guarantee’ is ‘on demand’ and payable as if a ‘principal debt’
	2. So once the borrower defaults, the bank can immediately demand performance from the guarantor ([[McGuinness v Norwich and Peterborough Building Society [2010] EWHC 2989 (Ch)]]).
2. If the contract between bank and borrower (the primary contract) is void (or if the borrower’s obligation is discharged), the guarantor’s obligation will fall away.
	1. A bank will therefore usually include a provision that the guarantee survives failure of the underlying obligation
	2. Also an indemnity within the guarantee document in order to create a primary obligation on the ‘guarantor’ if the guarantee fails.
3. If the contract between bank and borrower is varied in any material way without the guarantor’s consent, the guarantor is released from the guarantee (even if the variation was not prejudicial to the guarantor).
	1. Similarly, certain acts which might be prejudicial to the guarantor (e.g., if the bank fails to register security for the debt) will void the guarantee.
	2. [[Triodos Bank v Ashley Charles Dobbs [2005] EWCA Civ 630]]: the court decided that in respect of a guarantee purporting to allow “any amendments, variation, waiver or release from an obligation”, any amendment or variation must be ‘within the general purview of the original guarantee’.
	3. In [[Maxted, Lorimer v Investec Bank PLC [2017] EWHC 1997 (Ch)]], the High Court held that amendments to a loan (including an increase in amount and extension of the term) were within the purview of guarantees given by the borrowing company’s directors.
	4. The judge in [[Maxted, Lorimer v Investec Bank PLC [2017] EWHC 1997 (Ch)]] confirmed that if facility amendments were beyond the purview of the guarantees, this could be cured by the guarantors consenting to them (so the bank will ask guarantors to do this).

Other rights – usually waived or postponed:

1. Once a guaranteed debt has crystallised, the guarantor can make payment and claim indemnity from the obligor without waiting for a demand for payment of the debt. This is the case even if the guarantee requires payment only on demand (_[Thomas v Nottingham Incorporated Football Club Ltd [1972] Ch 596](https://uk.westlaw.com/D-000-5038?originationContext=document&transitionType=PLDocumentLink&contextData=(sc.Default)&ppcid=9fc18fbc2d79468f9bd5272f7e22e9db)_).
2. A guarantor may use most rights of set-off or counterclaim which the borrower has against the bank to reduce its liability under guarantee.
	1. Where the underlying obligor's payment obligations are satisfied by way of set-off against the creditor's corresponding liabilities, the guarantor is entitled to that right of set-off and will therefore be discharged from its obligations (_[BOC Group plc v Centeon LLC [1999] 1 All ER (Comm) 53](https://uk.westlaw.com/D-000-4199?originationContext=document&transitionType=PLDocumentLink&contextData=(sc.Default)&ppcid=9fc18fbc2d79468f9bd5272f7e22e9db)_).
3. Once paid out under the guarantee, a guarantor will be entitled to reimbursement from the borrower.
	1. There is an implied contract between the guarantor and the obligor that the obligor will provide such an indemnity (_[Re a Debtor (No.627 of 1936) [1937] Ch 156](https://uk.westlaw.com/D-000-5037?originationContext=document&transitionType=PLDocumentLink&contextData=(sc.Default)&ppcid=31b1b10b11a346b28acbfa5d800fec19)_).
4. Guarantor entitled to any security the bank holds for the borrower’s debt, under the doctrine of **subrogation** (equitable remedy to prevent unjust enrichment).
	1. Subrogation arises only once a guarantor has paid the full amount for which it is liable under the guarantee.
	2. Subrogation allows the guarantor to assume all the rights the lender has in relation to the borrower under the underlying contract.
	3. Once the guarantor has repaid the beneficiary, it is entitled to step into the shoes of the beneficiary and take the benefit of any rights of set-off and any security that the beneficiary has taken from the underlying obligor (_[Craythorne v Swinburne (1807) 14 Ves 160](https://uk.westlaw.com/D-000-5042?originationContext=document&transitionType=PLDocumentLink&contextData=(sc.Default)&ppcid=9fc18fbc2d79468f9bd5272f7e22e9db)_).
5. If there is more than one guarantor of the debt, any guarantor that pays out will have a right to claim back a share of the payment from co-guarantors (“right of contribution”).

The guarantee document should postpone the rights until such time as the bank has been repaid in full and no longer requires the security. It will also want any obligation of contribution to be waived in respect of any subsidiary it wants to sell.

### Drafting guarantee/ Indemnity

- If there is any uncertainty, the courts will presume that the interpretation that is less onerous for the giver of the document is correct.
- When distinguishing between indemnities and guarantees, the courts have traditionally looked at the extent to which the promisor is connected with the underlying transaction.
- A promisor unconnected with the underlying transaction, except by means of a promise to pay, has been held to be a guarantor, while a promise made by someone who will derive some benefit from the transaction was an indemnity (_[Couturier v Hastie (1852) 8 Exch 40](https://uk.westlaw.com/D-000-4146?originationContext=document&transitionType=PLDocumentLink&contextData=(sc.Default)&ppcid=31b1b10b11a346b28acbfa5d800fec19)_).
- The courts also consider the extent to which the promise can be construed as being the main purpose of the transaction (a guarantee) or incidental to the main purpose of the transaction (an indemnity) (_[Harburg India Rubber Comb Co v Martin [1902] 1 KB 778](https://uk.westlaw.com/D-000-5044?originationContext=document&transitionType=PLDocumentLink&contextData=(sc.Default)&ppcid=31b1b10b11a346b28acbfa5d800fec19)_).
- Identifying a guarantee involves making a distinction between the promisor having a mere motive for making the promise and having a “real interest” in (that is, deriving actual benefit from) the underlying transaction (_[Pitts v Jones [2007] EWCA Civ 1301](https://uk.westlaw.com/D-000-2980?originationContext=document&transitionType=PLDocumentLink&contextData=(sc.Default)&ppcid=31b1b10b11a346b28acbfa5d800fec19)_).

```ad-defn
title: Principle of co-extensiveness
The key feature of a guarantee that a guarantor is only liable to the beneficiary to the same extent as the underlying obligor.
```

#### Principle Debtor

A so-called principal debtor clause states, broadly, that a guarantor will be liable to the lender as if it were the principal obligor. This allows the lender to treat the guarantor as a debtor in certain circumstances.

The generally accepted view is that a principal debtor clause is unlikely to convert a guarantee into an indemnity (_[Carey Value Added, S.L. v Group Urvasco, S.A. [2010] EWHC 1905](https://uk.westlaw.com/D-000-1341?originationContext=document&transitionType=PLDocumentLink&contextData=(sc.Default)&ppcid=31b1b10b11a346b28acbfa5d800fec19)_). If the beneficiary wants an indemnity, it should expressly include one.

### General Considerations

- Governing law of the guarantee should if possible mirror that of the other loan documents.
- If the contract is legally a guarantee, it must be evidenced in writing before it can be enforced (Statute of Frauds 1677, s 4).
- As a contract, a guarantee is enforceable only if it is given for **consideration** (potentially void for past consideration if it is pre-dated by the obligation). So create as deed.
	- If a guarantee is executed as a deed, the guarantor will be bound from the date on which the deed is delivered.
- A guarantee should be expressed as ‘continuing’ to avoid the rule in ‘Clayton’s case’ and to help it to survive variations to the primary obligation.
	- Generally, receipts from the borrower into an account will discharge the liabilities in the order in which they were incurred, according to the rule in _[Devaynes v Noble, Clayton's case (1816) 1 Mer 529](https://uk.westlaw.com/D-000-4111?originationContext=document&transitionType=PLDocumentLink&contextData=%28sc.Default%29&comp=pluk)_.
	- In the context of continuing guarantees, it is not necessary under English law to state whether the guarantor can revoke its obligations under the guarantee.
- The guarantee should provide that the bank’s evidence of the borrower’s liability is conclusive.
- As with any other contract, a company must have the requisite power to enter into a guarantee, and its officers must be properly authorised.
	- Consider **s 172** duty to promote the success of the company.
	- The higher the risk that a company is assuming by entering into a contract, the greater the commercial benefit (sometimes called “corporate benefit”) obtained from the contract needs to be.
		- It is assumed that, if a parent company guarantees or indemnifies the obligations of a subsidiary (a “downstream” guarantee), there is sufficient commercial benefit because of the increased profitability of the subsidiary, higher dividends and increased value of the shares.
		- If a subsidiary guarantees or indemnifies the obligations of a parent company (an “upstream” guarantee), this is more difficult.
			- Subsidiaries often rely on parent companies for treasury services, which can justify an upstream guarantee.
			- The guarantee or indemnity provided by each subsidiary helps reduce the funding costs for the group as a whole.
- A guarantee is capable of being ‘financial assistance’ under the provisions of CA 2006, ss 678–680.
	- It is unlawful for a public company whose shares are being, or have been, acquired (or for any of that company's subsidiaries) to give financial assistance directly or indirectly for the purpose of that acquisition unless certain exceptions apply.
	- The term “financial assistance” includes the provision of guarantees, security or indemnities and any form of assistance whereby the net assets of the assisting company are reduced to a material extent or where the assisting company has no net assets.
	- Penalties include the guarantee/ indemnity being void, and directors being liable for a fine and $\leq 2$ years imprisonment.

```ad-test
title: Rule in Clayton's case

Technically, the rule applying to withdrawals from a current bank account is the rule in [[Clayton’s Case (1816) 1 Mer 529]]. Grant MR stated: ‘it is the sum first paid in that is first drawn out.’ The rule is commonly described as ‘the first in, first out’ rule.
```

```ad-example
T misapplies £1,000 of trust fund A and pays it into a current bank account (‘the account’). T misapplies £1,000 of trust fund B and pays it into the account. T withdraws £1,000 from the account and uses it to purchase shares. T misapplies £1,000 of trust fund C and pays it into the account. T withdraws £1,000 from the account and dissipates it. £1,000 is still credited to the account.
```

```ad-important
title: Illegality
Azimut-Bennetti v Healay – if the underlying obligation was void for public policy (e.g. as a penalty), then the guarantee will also be void for reasons of public policy and there is nothing that the guarantee can say to change it.
```

### Insolvency Act 1986

A guarantee is arguably capable of being a transaction at an undervalue (because, unlike a borrower granting security, it usually increases the guarantor’s liabilities) and, in limited circumstances (e.g., where the guarantor had previously only given third party security, with no guarantee), a preference, and so being set aside under IA 1986, ss 238 and 239 respectively.

### Counter-indemnity

There is no case law that says that payment under an indemnity will give rise to the same right to be counter-indemnified as applies in the case of a guarantee, but it seems likely that it does (_[Berghoff Trading Ltd v Swinbrook Developments Ltd [2009] EWCA Civ 413](https://uk.westlaw.com/D-009-8767?originationContext=document&transitionType=PLDocumentLink&contextData=(sc.Default)&ppcid=9fc18fbc2d79468f9bd5272f7e22e9db)_).

However, as an indemnity is not co-extensive with the underlying obligations, the indemnifier may be liable to pay more than the underlying obligor. There would therefore be a question about whether the counter-indemnity would be limited to the amount payable by the underlying obligor. Consequently, it is not unusual, when entering into a combined guarantee and indemnity, to insist that a counter-indemnity agreement between the guarantor and the underlying obligor is also entered into.

## Comfort Letters

Suppose a parent company/ other potential obligor refuses to provide a guarantee. The bank may demand a comfort letter (“support letter”/ “letter of intent”) from the obligor. This could be a written acknowledgement that the subsidiary is undertaking the obligations created by the loan, to a statement of intention to maintain an interest in, and support for, a subsidiary, and to ensure it is capable of fulfilling those obligations ("keep-well agreement").

Not normally intended to be legally binding. Phrasing usually deliberately vague enough not to be enforceable under contract law. Consider offer and acceptance, ICLR and consideration.

In the case of [[Re Atlantic Computers plc (in administration); National Australia Bank Ltd v Soden [1995] BCC 696]], it was held that the common intention of the parties to a comfort letter must be ascertained by reading it as a whole. So include wording like ‘an expression of present intention by way of comfort only’.

## Negative Pledge

Arguably a restriction on how the borrower may use its assets. Technically not a security interest (although it might provide a claim in tort for damages against a third party which induces a borrower to breach the prohibition, and there is an argument that the third party holds any such security on trust for the negative pledge holder).

## Retention of Title

A retention of title clause allows a seller to retain legal title to goods which have been supplied to a buyer until the buyer settles its account. If payment is not forthcoming, the seller can recover the goods from the buyer.

This may undermine a bank's security, so it is common for the bank to require representations and/or warranties to the effect that the borrower is not party to any agreements which contain a retention of title clause.

## Set-off

A right to set a debt owed by a creditor to a debtor against the debtor’s debt, and so reduce or extinguish that debt.

```ad-tip
Basically the right to take money from the borrower's current account if it defaults on its loan. 
```

3 ways in which a bank is likely to have a right of set-off against the borrower:

| Means                      | Details                                                                                                                                                 |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Equitable right of set-off | A bank may set off a liquidated debt owed to it by a borrower against a liquidated debt owed by it to that borrower.                                    |
| Contractual set-off        | Most security documents supporting a loan will enhance the equitable right of set-off by allowing the bank to set off unliquidated (contingent) claims. |
| Set-off on liquidation     | r 490 Insolvency Rules 1986 provides for mandatory set-off. Basically, any ‘mutual’ credits, debts or dealings can be set off so long as the bank did not know of the petition for insolvency against the borrower when it gave credit. Set off of contingent claims also allowed.                                                                                                                                                         |

```ad-note
The right of set-off is particularly important if a debtor is in danger of becoming insolvent (but no petition has been lodged), since it allows access to the debtor’s unsecured assets (ie, cash) without risk of being a transaction at an undervalue or a preference under IA 1986, ss 238 and 239.
```

### Banker's Right of Combination

There is an implied right under common law which is peculiar to banks and which allows them, subject to contrary agreement, to combine two or more accounts of a borrower. So an overdrawn account and an account in credit can be combined.

## Why Take Security

Aside from increasing the likelihood of getting repaid, there are other reasons for taking security:

### Appointing administrator/ Receiver

If a bank wants to enforce security it will invariably do so through a third party, and usually when the borrower is, or is about to become, insolvent.

#### Administration pre-EA 2002

The administration procedure was introduced by the IA 1986. For an administrator, the first, and key, purpose was to ensure ‘the survival of the company, and the whole or any part of its undertaking, as a going concern’. The administrator was given power to effect a moratorium on the rights of all secured and unsecured creditors, to help further this purpose.

Banks didn't like this, so successfully lobbied for the right to block an administration order if they held security (which included a floating charge) over all, or substantially all, of a company’s assets. This was achieved by appointing an administrative receiver under IA 1986 (s 9).

#### Administrative Receiver pre-EA 2002

```ad-statute
title: s 29(2) IA 1986
“Administrative receiver” means—
- (a) a receiver or manager of the whole (or substantially the whole) of a company’s property appointed by or on behalf of the holders of any debentures of the company secured by a charge which, as created, was a floating charge, or by such a charge and one or more other securities; or
- (b) a person who would be such a receiver or manager but for the appointment of some other person as the receiver of part of the company’s property.
```

The term ‘debenture’ ‘includes … bonds and any other securities of a company …’. So long as a bank held security (which included a floating charge) over ‘all or substantially all’ of a borrower’s assets, it could appoint an administrative receiver, with wide-ranging powers to manage the business and sell assets to repay the bank debt and, crucially, the power to block an administration order and moratorium.

#### Administration post-EA 2002

New purposes of administration (cascading downwards):

1. attempt to rescue the company as a going concern – if this is not reasonably practical, or would not produce the best result for the creditors as a whole;
2. attempt to achieve a better result for creditors than if the company were wound up; and (only if the administrator thinks the first two purposes are not reasonably practical)
3. realise the company’s property to distribute to secured or preferential creditors, so long as the administrator does not unnecessarily harm the interests of the creditors as a whole.

These apply regardless of who appoints the administrator. Administrator can be appointed:

1. By court order
2. By [[Qualifying Floating Charge]] holder. Floating charge document must state that EA 2002 applies to it/ purport to allow the holder to appoint an administrator or administrative receiver.

#### Administrative Receivership post-EA 2002

In addition to any floating charges created before 15 September 2003, there are eight ‘exceptions’ under which an administrative receiver may still be appointed:

1. ‘capital market’ exception,
2. ‘public–private partnership’ exception,
3. ‘utility projects’ exception,
4. ‘urban regeneration projects’ exception,
5. ‘project finance’ exception,
6. ‘financial markets’ exception,
7. ‘protected railways and other companies’ exception and
8. ‘registered social landlord’ exception.

Applies only to specialist financing.

```ad-summary
Where the bank holds a ‘qualifying floating charge’ created after 15 September 2003, but does not fall within one of the eight statutory exceptions, it will be permitted to appoint an administrator only to realise security on insolvency. The bank’s administrator must consider the two prior purposes of administration before realising assets on the bank’s behalf.
```

### Peripheral Benefits

- Taking fixed security will help to prevent a borrower disposing of assets and ensure they remain in the business to create value, enhancing disposal undertakings.
- It may deter other banks from lending to the borrower, enhancing the negative pledge.
- It may also dissuade unsecured creditors from taking action to wind up the borrower.
- Personal security from directors of a small company may act as an incentive for them to work to make the business prosper.

### Costs

Secured loans will carry less risk for a bank than unsecured loans, and compliance with regulatory capital requirements will make some types of secured loan ‘cheaper’ than unsecured loans.

## Bank's Perspective

- Taking security is expensive and time-consuming. Investment grade loans are unsecured; highly leveraged loans almost always secured.
- A bank’s solicitor should check that the borrower and any other party providing security has capacity to do so (there may be restrictions in the articles).
- Check there is no existing negative pledge.

## Borrower's Perspective

- Usually liable for all reasonable costs of providing security, including solicitors' fees and registration costs.
- Two concessions frequently negotiated:
	1. In acquisition financings, only share security is provided at closing (when the loan is available). Borrower given a period of time (up to 120 days) to provide remaining asset security.
	2. Common to agree security principles early in negotiation – pre-agreed parameters for security, costs and any obligations on the borrower.

# Taking Security

3 steps to creating a valid security interest:

1. Creation – agreement to create a particular security interest between debtor and creditor.
2. Attachment – ensuring the security interest binds on specific assets
3. Perfection – ensuring validity against third parties and priority.

Perfection and priority are here examined.

## Registration

The safest way to secure an asset is to take possession of it (take a “pledge”). But most loan security is non-possessory. To stop a secured asset being sold on/ re-secured, there is a statutory requirement for the registration of non-possessory security interests.

### CA Regime

The requirement for companies to register certain security interests at Companies House is long-standing. The primary aim is a mechanism to give third parties notice of the security and thereby make it valid against their claims.

The registration regime changed on 06/04/13. It used to be compulsory to register most charges, now it is voluntary. But if the charge is not registered in time, there are consequences (e.g., may become void).

#### What to Register

The registration requirement applies to ‘charges’ created by companies and LLPs. The term ‘charge’ is defined to include mortgages (s 859A(7)) and security assignments. By implication, registration is not required for pledges or liens for which actual or constructive possession of the secured asset by the security holder operates as notice to third parties.

Guarantees don't need registering, mortgages and fixed/ floating charges usually do. For other stuff (loans, pledges), solicitors will usually register out of an abundance of caution.

All charges (remember this includes mortgages) may be registered, with the following three (minor) exceptions (s 859A(6)):

1. a charge in favour of a landlord on a cash deposit given as security in connection with the lease of land;
2. a charge created by a member of Lloyd’s to secure its obligations in connection with its underwriting business;
3. a charge excluded by any other Act.

```ad-statute
title: s 859A CA 2006 - Charges created by a company

(1) Subject to subsection (6), this section applies where a company creates a charge.

(2) The registrar must register the charge if, before the end of the period allowed for delivery, the company or any person interested in the charge delivers to the registrar for registration a section 859D statement of particulars.

(3) Where the charge is created or evidenced by an instrument, the registrar is required to register it only if a certified copy of the instrument is delivered to the registrar with the statement of particulars.

(4) “The period allowed for delivery” is 21 days beginning with the day after the date of creation of the charge (see section 859E), unless an order allowing an extended period is made under section 859F(3).

(5) Where an order is made under section 859F(3) a copy of the order must be delivered to the registrar with the statement of particulars.

(6) This section does not apply to—
- (a) a charge in favour of a landlord on a cash deposit given as a security in connection with the lease of land;
- (b) a charge created by a member of Lloyd's (within the meaning of the Lloyd's Act 1982 F2) to secure its obligations in connection with its underwriting business at Lloyd's;
- (c) a charge excluded from the application of this section by or under any other Act.

(7) In this Part—

“cash” includes foreign currency,

“charge” includes—
- (a) a mortgage;
- (b) a standard security, assignation in security, and any other right in security constituted under the law of Scotland, including any heritable security, but not including a pledge, and

“company” means a UK-registered company.
```

```ad-warning
Charges over shares are, strictly speaking, exempt from registration under the Companies Act 2006 because of the effect of the Financial Collateral Arrangements (No. 2) Regulations 2003 (as amended). However, in practice, security over shares is usually registered, even when registration is not strictly required, because often the share security document covers more than just the shares, thereby giving rise to the concern that payments on the shares (e.g. dividends) may be book debts and, therefore, the security may be registrable.
```

#### Who Registers

Either the company or “any person interested in the charge” (s 859A(2)). This includes the charge-holder as well as the legal advisors to the company or charge-holder. In practice, the charge-holder register the charge.

#### Requirements

```ad-action
Once agreement has been entered into, the company/ any person interested in the charge should deliver (s 859A(2)):

1. A s 859D statement of particulars to Companies House (s 859A(2))
	- This will usually be Form MR01 for a company (or MR08 where there is no charge instrument) or the equivalent forms LLMR01 and LLMR08 for a limited liability partnership.
2. A certified copy of the instrument creating the charge (s 859A(3))
3. The requisite fee
```

s 859G allows certain details to be obscured in the certified copy of the charge instrument (known as ‘redaction’), such as

- Personal information relating to an individual
- Bank account number of a person/ individual
- Signature.

The paragraph certifying it as a true copy of the original should state ‘save for material redacted pursuant to s 859G’.

#### Time Limit for Registration

The registration documents must be delivered **before the end of 21 days beginning with the day after the date of creation of the charge** (s 859A(4)).

If there is a defect with the submission, it must be corrected within the 21-day time limit for submission. whilst there is provision at s 859F for the company (or a person interested) to apply to court for an extension to the 21-day period, there is no guarantee it will be granted.

#### Late/ Inaccurate Delivery

Under [s 859F CA 2006](https://www.legislation.gov.uk/ukpga/2006/46/section/859F), the court has the power to extend the period for registration where the grounds of s 859F(2) are met:

>(a) that the failure to deliver those documents-  
>(i) was accidental or due to inadvertence or to some other sufficient cause, or  
>(ii) is not of a nature to prejudice the position of creditors or shareholders of the company, or  
>(b) that on other grounds it is just and equitable to grant relief.

The court will allow the register to be rectified provided this does not prejudice any other charges created between the date of creation of the unregistered charge and the date of eventual registration ([[Barclays Bank plc v Stuart Landon Ltd [2001] 2 BCLC 316]]).

If an application is successful, the charge will have priority only from the date of actual registration, so may lose priority due to the delay if other charges have been registered in the meantime.

The court has also refused to allow a charge to be registered late, where the time elapsed is too long ([[Victoria Housing Estates Ltd v Ashpurton Estates Ltd [1982]]]).

The court has power:

- Under s 859M to allow rectification of a statement/ notice delivered to the Registrar for inaccurate details.
- Under s 859N if the charging document was defective/ wrong document was sent, can be replaced.

#### Effect of Valid Registration

A validly registered charge is valid against a liquidator, administrator and any creditor of the company that created the charge. But it will not prevent the terms of a charge being challenged, challenge as a preference, transaction at an undervalue or similar.

The form MR01 also has a ‘tick box’ for noting whether the terms of the charge include a negative pledge. The intention is to put anyone who searches the register on notice of the negative pledge.

#### Effect of Invalid Registration

Failure to register a charge within the 21-day period means (s 859H):

1. Security is void against a liquidator, administrator and any creditor
2. The amount secured by the void security becomes immediately payable.

The charge remains valid against the company creating it unless and until that company goes into liquidation or administration. However, the money secured by the charge becomes payable immediately (CA 2006, s 859H(4)).

#### Documents

The company must keep the following documents available at its registered office (s 859P) or SAIL (s 859Q(2)):

1. a copy of every instrument creating a charge capable of registration under the CA 2006;
2. a copy of every instrument that amends or varies a charge capable of registration under the CA 2006;
3. a copy of any documents containing particulars required for registration if those particulars are not in the charge instrument;
4. a copy of any translation required as part of the registration (see CA 2006, s 1105).

The documents may be certified copies (other than the translation) and be available without charge to a creditor or shareholder, and to any other person on payment of a prescribed fee.

#### Security Release

Some security documents may purport to allow a bank to retain the security for a period even after repayment as ‘insurance’ against the repayment being clawed back under the IA 1986, or may deem the debt and security to continue after repayment if the security agent considers clawback a possibility. The efficacy of such provision is questionable.

When the loan is repaid by the company to the lender, a person with an interest in the registration of the charge (such as a director of the company) may, but is not obliged to, complete, sign and send **Form MR04** to the Registrar of Companies at Companies House. This is usually done to ensure the company's file is up-to-date.

Security might also be released to allow for disposal of a particular asset. Release is usually achieved by a deed of release drawn up by the borrower’s solicitor. If the lender decides to release the company’s property from the charge or allows the company to sell the asset covered by the charge, a person with an interest in the registration of the charge (such as a director of the company) must complete, sign and send **Form MR05** to the Registrar of Companies at Companies House.

#### Property Already Subject to Charge

The current regime allows a company (or person interested) to register a charge which already exists on property it acquires (assuming the charge would have been capable of registration if the company had created it). There is no time limit, and non-registration is not an offence.

#### Overseas Companies

Registration of charges applies to all charges created by UK companies/ LLPs, even if the secured assets are overseas.

### Asset-specific Registration Requirements

| Asset    | Registration                                                           |
| -------- | ---------------------------------------------------------------------- |
| Land     | Registered land registered at the District Land Registry.              |
| Ships    | Registered at ship's port of registration (Merchant Shipping Act 1894) |
| Aircraft | Aircraft Mortgage Register                                             |
| IP       | Various statutory provisions.                                                                        |

### Security Created by Individuals

The Bills of Sale Acts 1878 and 1882 impose registration requirements on security created by individuals.

```ad-note
The Acts require most written, non-possessory charges given by an individual or a partnership over tangible property to be registered in prescribed form at the Supreme Court as a bill of sale.
```

IA 1986, s 344 requires most forms of assignment of a trader’s book debts to be registered as a bill of sale if they are to be valid against a trustee in bankruptcy.

## Priority of Security

### Priority Between Charges and Mortgages

- Fixed charges and mortgages rank in order of creation (if properly registered).
- At common law, a legal mortgage takes priority over an existing equitable security interest only if the legal interest was taken bona fide, for value and without notice of the prior equitable security.
- Registration gives notice to anyone who has, or ought to have, searched the register, which will usually protect a prior registered equitable security.

### Fixed and Floating Charges

- Fixed charge will rank in priority to a floating charge
- Note the floating charge could contain a negative pledge $\rightarrow$ then if the later fixed charge holder has actual/ constructive notice of the prohibition through registration, the floating charge would rank first.
- Priority between floating charges governed by their time of creation.
- The date of the charge from which priority can be calculated is the date of creation, not the date of registration
	- A search made on the day of registering a charge might not show a charge created within 21 days which could take priority.

### Security Over Land

- Under the registered land system, the bank proposing to take a legal security must complete a “priority search” at the Land Registry.
- This shows any existing encumbrances over the registered land, as well as actual/ proposed dealings with land.
- If no other encumbrances/ dealings/ priority searches are revealed, the bank has 30 working days within which to register the new legal mortgage and take priority.
- Registration then ensures priority even over an earlier dated unregistered legal mortgage without the benefit of a priority search.

### _Dearle V Hall_

[[Dearle v Hall (1828) 3 Russ 1]] establishes a rule of priority applicable to all assignments or charges of equitable interests and any interest in debts.

```ad-action
To ensure priority, notice of the charge or assignment must be given to the third party which owes the obligation.
```

The same rule applies to charges. The rule will not apply, however, where a subsequent assignee (or chargee) knows of the earlier assignment when taking its assignment. Thus, registration of the security at the Companies Registry will usually defeat the rule.

## Contractual Subordination

### Contractual Priority Arrangements

Possible for creditors to decide between themselves the order in which they will benefit from claims against a defaulting debtor. Priority arrangements frequently used in large financings with layers of debt.

Document creating rights known as an “intercreditor agreement”/ “subordination agreement”/ “deed of priorities”.

### Typical Arrangement

Participants restricted so that:

- Participating lenders divided into an agreed order of priority (tranches) for repayment of their credit.
	- Senior creditors
	- Mezzanine
	- Loan notes
	- High yield.
- No participating bank may enforce security or otherwise proceed against the borrower without the agreement of senior banks/ majority consent
- When security is enforced:
	- Subordinated creditors contractually agree not to claim against the borrower until the senior creditors are repaid (“contingent debt subordination”).
	- Subordinated creditors agree to hold any money they receive on trust for senior creditors (known as a ‘turnover trust’).
		- More robust than contingent debt subordination.
- The pooled money will then be distributed in accordance with the agreement.

```ad-question
title: Does a turnover trust create a proprietory interest over the debt which requires registration as a charge under CA 2006?
[[SSSL Realisations Limited [2004] EWHC (Ch) 1760]] held that the turnover trust in that case did not create a charge: it did create a proprietory right, but since it was limited to the debt owed there was no charge over the ‘junior’ creditor’s property.

Some practitioners register anyway just to be sure. 
```

There is also **structural subordination**: ordinary shareholders automatically subordinated to debt-holding creditors because debts must be repaid before capital can be realised.

Subordination between shareholders through preference shares.

### When is Contractual Subordination Used

- $\uparrow$ risk $\implies$ $\uparrow$ margin. All banks want a diversified spread of risk.
- Contractual subordination might also be used where an unsecured bank requires any debts to a borrower’s directors or parent company to be subordinated to its own.
- Existing bank may agree to subordination to a new bank to secure new funding to help the business.

## Tacking

```ad-defn
Tacking is the ability to secure new advances under existing security.
```

Depends on the asset:

### Registered Land

LRA 2002, s 49.: a mortgage/ charge holder can tack if:

1. it has not received notice of the subsequent security; or
2. the new advance is under an obligation already on the register when the subsequent charge was created; or
3. the maximum amount of the first charge was agreed and on the register when the subsequent charge was created.

### Personalty

Mortgaged/charged personalty is subject to the provisions of LPA 1925, s 94. Any actual or constructive notice of a subsequent mortgage/charge will end a prior mortgagee’s/ chargee’s right to tack unless:

- an arrangement has been made to that effect with the subsequent mortgagees; or
- where the mortgage imposes an obligation on the first mortgagee to make further advances.

## Ruling Off Accounts

When a borrower makes a payment to a bank, the borrower may instruct the bank as to which account it should be appropriated or which loan should be repaid.

In the absence of any specific agreement, the rule in [[Clayton’s Case (1816) 1 Mer 529]] (Devaynes v Noble (1816) 1 Mer 572) applies. Money paid to the bank will discharge the borrower’s debt in the chronological order in which the debt was incurred. But this might disadvantage the bank:

1. May repay a secured loan rather than an unsecured loan, leaving the bank in a more precarious position than if the unsecured loan was repaid first
2. New security may be more vulnerable to be set aside than older “hardened” security.
3. In certain circumstances, new advances would rank behind a second loan to another lender. So a repaid and redrawn RCF may lose priority to a new loan.

- To avoid (1) and (2), the bank may insist on choosing where payments are appropriated (if not received in full).
- (3) dealt with by allowing a bank to “rule off” an account if it learns the borrower has taken a second secured loan.
	- Original secured loan is preserved ("ruled-off") and not treated as repaid by any amounts received from the borrower.
	- Security should be specified as securing all amounts due from time to time from the borrower to the bank.
	- Insert negative pledge clauses.

### Clayton & Guarantees

Subject to contrary agreement, once a guaranteed liability has been fixed in value, any payment by the borrower to the bank will be deemed to reduce the guaranteed debt.

```ad-action
Can be avoided by specifying the guarantee to be ‘continuing’, or alternatively an ‘all monies guarantee’.
```

## Fixed or Floating

Floating charge advantages (for the bank):

- Allows a borrower to deal freely with the charged assets in the ordinary course of business
- May allow the bank to appoint an administrative receiver
	- After changes made by the EA 2002, this is relevant only to ‘specialised’ financial structures.
- The holder of a ‘qualifying floating charge’ (as defined by IA 1986, Sch B1, para 14) can appoint an administrator using an out-of-court procedure.

```ad-defn
title: “Lightweight”/ “Phantom” floating charge
Charge taken primarily for the purpose of allowing the bank to appoint an administrative receiver.
```

Floating charge disadvantages:

- On insolvency, a floating charge ranks behind any fixed security/ preferential creditors.
- Floating charge may be vulnerable to later fixed charges, even if containing a registered negative pledge.
- Can be set aside under wide circumstances
- Some of the proceeds available allocated to the prescribed part fund
- Ranks behind liquidator's expenses
- Borrower free to deal with assets until crystallisation.

See also [[Common Securities]].

## Hardening Periods

```ad-defn
title: Hardening period
A period during which the security is vulnerable to provision in IA 1986 for setting aside certain transactions. 
```

Possible grounds for setting aside security:

- Transaction at an undervalue (s 238 IA 1986)
- Preferences (s 239 IA 1986)
- Floating charges (s 245 IA 1986)

See [[Business Law and Practice/Insolvency/Voidable Transactions]].

## Capacity

Before lending, check the capacity of the borrower to provide security.

The powers and limitations on trustees will be found in the trust deed.

```ad-statute
title: s 16 TA 1925 - Power to raise money by sale, mortgage, &c.

(1) Where trustees are authorised by the instrument, if any, creating the trust or by law to pay or apply capital money subject to the trust for any purpose or in any manner, they shall have and shall be deemed always to have had power to raise the money required by sale, conversion, calling in, or mortgage of all or any part of the trust property for the time being in possession.

(2) This section applies notwithstanding anything to the contrary contained in the instrument, if any, creating the trust, but does not apply to trustees of property held for charitable purposes, or to trustees of a settlement for the purposes of the Settled Land Act, 1925, not being also the statutory owners.
```

So trustees are granted the power to grant security provided that borrowing is authorised and for the purpose of the trust, regardless of what the trust deed says.

## Corporate Benefit

A bank often requires additional security from a borrower's parent, subsidiary, or sister company. The company providing the guarantee/ indemnity/ security must prove it derives sufficient “corporate benefit” from granting the security. Consider s 172 duty to promote the success of the company.

A subsidiary securing its parent (e.g., an ‘up-stream’ guarantee) could argue that the support from its parent (e.g., financial, marketing, product development) provides sufficient corporate benefit. This argument is more tenuous if the company is a small fish in a large group pond, but can be strengthened by a down-stream support letter.

If a company believes there is insufficient corporate benefit to provide security, there is authority to suggest that it may still be given, provided that:

1. the company’s shareholders unanimously direct the security to be given; and
2. the company is not insolvent either at the time of giving the security, or immediately following the giving of the security.

## Financial Assistance

### Definition

Refers to a company providing financial assistance for the purchase of its own shares. This includes financial assistance given by way of a gift, loan, guarantee, security or indemnity ([s 677 CA 2006](https://www.legislation.gov.uk/ukpga/2006/46/section/677)).

Financial assistance was defined in [[British and Commonwealth Holding PLC v Barclays Bank plc [1996] 1 WLR 1]] as

> “The section requires that there should be assistance or help for the purpose of acquiring the shares and that that assistance should be financial”.

Financial assistance was originally made unlawful to counter a practice whereby individuals were able to purchase cash rich companies by arranging for the target company to advance the cash to finance the acquisition. In effect, the company paid for its own acquisition.

### Prohibitions

CA 2006 **removed** the prohibition in relation to private companies, so now prohibition of financial assistance **only** applies in general to public companies.

- Both public companies and their private limited subsidiaries are prohibited from providing financial assistance for the purchase of shares in the public company ([s 678 CA 2006](https://www.legislation.gov.uk/ukpga/2006/46/section/678)).
- Public companies are also prohibited from providing financial assistance for the purchase of shares in their private limited **holding** companies ([s 679 CA 2006](https://www.legislation.gov.uk/ukpga/2006/46/section/679)).

The consequences of unlawful financial assistance are that the transaction will be held void and the company, and any officer in default, will be liable to a fine/ up to two years in prison.

```ad-important
The rules on financial assistance are relevant in the context of share purchases and do not apply where the buyer is acquiring the target company's assets.
```

#### Purpose

Financial assistance will only be prohibited by _[section 678](https://uk.westlaw.com/5-505-7258?originationContext=document&transitionType=PLDocumentLink&contextData=(sc.Default)&ppcid=52c063520c5f48d8a198d13504dc80c1)_ or _[679](https://uk.westlaw.com/6-506-2056?originationContext=document&transitionType=PLDocumentLink&contextData=(sc.Default)&ppcid=52c063520c5f48d8a198d13504dc80c1)_ if it is given “for the purpose of” the acquisition of shares or to reduce or discharge previous liability in relation to an acquisition. The company must have **intended** to facilitate the acquisition by giving the assistance.

#### Time

The prohibition on financial assistance in _[section 678](https://uk.westlaw.com/5-505-7258?originationContext=document&transitionType=PLDocumentLink&contextData=(sc.Default)&ppcid=52c063520c5f48d8a198d13504dc80c1)_ and _[section 679](https://uk.westlaw.com/6-506-2056?originationContext=document&transitionType=PLDocumentLink&contextData=(sc.Default)&ppcid=52c063520c5f48d8a198d13504dc80c1)_ is not limited in time.

#### Re-registration

Public companies may be able to re-register as private to give financial assistance for the acquisition of their own shares. Where a public company has re-registered as a private company after the shares have been acquired and it is a private company at the time the post-acquisition assistance is given, the _[section 678](https://uk.westlaw.com/5-505-7258?originationContext=document&transitionType=PLDocumentLink&contextData=(sc.Default)&ppcid=52c063520c5f48d8a198d13504dc80c1)_ prohibition will not apply.

### Exceptions

There are some exceptions, but these are narrowly construed.

#### Unconditional Exceptions

[s 681 CA 2006](https://www.legislation.gov.uk/ukpga/2006/46/section/681) contains a wide list of unconditional exceptions, mainly relating to financial assistance being offered for procedures which are authorised in other sections (e.g., redemption of shares, reduction of capital).

#### Conditional Exceptions

[s 682 CA 2006](https://www.legislation.gov.uk/ukpga/2006/46/section/682) lists a number of “conditional” exceptions, which apply only if the company has net assets and either:

1. Those assets are not reduced by the giving of financial assistance, or
2. To the extent that those assets are reduced, the assistance is provided out of distributable profits.

#### Principal Purpose and Incidental Part of a Larger Purpose

One example of a conditional exception is financial assistance by a company for the purposes of an employee share scheme, provided this is made in good faith in the interests of the company or its holding company (s 682(2)(b)).

There are exceptions set out in s 678(2) and (3) and s 679 (2) and (3) which are designed to ensure that the prohibition in s 678(1) and s 679 (1) does not prohibit genuine commercial transactions that are in the interests of the company.

These provide that financial assistance is not prohibited:

- If the principal purpose of the assistance is not to give it for the purpose of an acquisition of shares, or where the assistance is incidental to some other larger purpose of the company; and
- In either case, where the financial assistance is given in good faith in the interests of the company.
	- To satisfy the good faith test, the officers procuring the company to give the financial assistance must act in the genuine belief that the assistance is being given in the company's interests.

These exceptions can be difficult to rely on ([[Brady v Brady [1989] AC 755]]) since they are extremely narrowly construed by the courts.

```ad-statute
title: s 678 - Assistance for acquisition of shares in public company

(1) Where a person is acquiring or proposing to acquire shares in a public company, it is not lawful for that company, or a company that is a subsidiary of that company, to give financial assistance directly or indirectly for the purpose of the acquisition **before or at the same time** as the acquisition takes place.

(2) Subsection (1) does not prohibit a company from giving financial assistance for the acquisition of shares in it or its holding company if—
- (a) the company's principal purpose in giving the assistance is not to give it for the purpose of any such acquisition, or
- (b) the giving of the assistance for that purpose is only an incidental part of some larger purpose of the company,

and the assistance is given in good faith in the interests of the company.

(3) Where—
- (a) a person has acquired shares in a company, and
- (b) a liability **has been incurred** (by that or another person) for the purpose of the acquisition,

it is not lawful for that company, or a company that is a subsidiary of that company, to give financial assistance directly or indirectly for the purpose of **reducing or discharging the liability** if, **at the time the assistance is given**, the company in which the shares were acquired is a public company.

(4) Subsection (3) does not prohibit a company from giving financial assistance if—
- (a) the company's principal purpose in giving the assistance is not to reduce or discharge any liability incurred by a person for the purpose of the acquisition of shares in the company or its holding company, or
- (b) the reduction or discharge of any such liability is only an incidental part of some larger purpose of the company,

and the assistance is given in good faith in the interests of the company.

(5) This section has effect subject to sections 681 and 682 (unconditional and conditional exceptions to prohibition).
```

```ad-statute
title: s 679 - Assistance by public company for acquisition of shares in its private holding company

(1) Where a person is acquiring or proposing to acquire shares in a private company, it is not lawful for a public company that is a subsidiary of that company to give financial assistance directly or indirectly for the purpose of the acquisition **before or at the same time** as the acquisition takes place.

(2) Subsection (1) does not prohibit a company from giving financial assistance for the acquisition of shares in its holding company if—
- (a) the company's principal purpose in giving the assistance is not to give it for the purpose of any such acquisition, or
- (b) the giving of the assistance for that purpose is only an incidental part of some larger purpose of the company,

and the assistance is given in good faith in the interests of the company.

(3) Where—
- (a) a person has acquired shares in a private company, and
- (b) a liability **has been incurred** (by that or another person) for the purpose of the acquisition,

it is not lawful for a public company that is a subsidiary of that company to give financial assistance directly or indirectly for the purpose of **reducing or discharging the liability**.

(4) Subsection (3) does not prohibit a company from giving financial assistance if—
- (a) the company's principal purpose in giving the assistance is not to reduce or discharge any liability incurred by a person for the purpose of the acquisition of shares in its holding company, or
- (b) the reduction or discharge of any such liability is only an incidental part of some larger purpose of the company,

and the assistance is given in good faith in the interests of the company.

(5) This section has effect subject to sections 681 and 682 (unconditional and conditional exceptions to prohibition).

```

### Types

_[section 677(1)](https://uk.westlaw.com/8-505-7474?originationContext=document&transitionType=PLDocumentLink&contextData=(sc.Default)&ppcid=52c063520c5f48d8a198d13504dc80c1)_ sets out a number of different heads of financial assistance:

- Financial assistance given by way of gift.
	- If there is some consideration, however inadequate, moving to the company, it will not be a gift. The transaction might still be caught by _[section 677(1)(d)](https://uk.westlaw.com/8-505-7474?originationContext=document&transitionType=PLDocumentLink&contextData=(sc.Default)&ppcid=52c063520c5f48d8a198d13504dc80c1)_ (material reduction in net assets).
- Financial assistance given by way of guarantee, security or indemnity (other than an indemnity in respect of the indemnifier's own neglect or default), or by way of release or waiver.
- Financial assistance given by way of loan or any other agreement under which any of the obligations of the person giving the assistance are to be fulfilled at a time when in accordance with the agreement any obligation of another party to the agreement remains unfulfilled.
- Any other financial assistance given by a company where the net assets of the company are reduced to a material extent by the giving of the financial assistance or the company has no net assets.
	- Assets and liabilities here should be given their actual values and not their book values.
	- For “material extent”, it is commonly accepted that less than 1% would fall outside the prohibition but 1% and over would amount to a material reduction.
		- This is the only _de minimis_ rule in s 677.

### Flowcharts

#### S 678

MERMAID1

#### S 679

MERMAID2

### Share Purchases

There are several situations which may raise financial assistance problems in the context of a share purchase (if transactions carried out for the purpose of assisting the acquisition of shares in the target – which is a public company/ private holding company of a public company giving financial assistance):

1. The target public company grants security over its assets in respect of a loan taken out by the buyer of shares.
2. The target public company repays its existing indebtedness under a loan agreement to its private holding company (the seller) at the time of the sale of the company.
	1. If the loan from the seller is repayable on demand, then this repayment will not be financial assistance.
	2. Else, acceleration of payment could amount to financial assistance.
3. Target public company sells assets to the buyer at the time of the sale of the company.
	1. If the company sells the assets at less than their market value (for example, at book value), this could be financial assistance insofar as there is a material reduction in the company's net assets (section 677(1)(d)(i)).
	2. If the target company leaves any of the consideration on the sale outstanding, this may amount to financial assistance by way of a loan “or any other agreement under which any of the obligations of the person giving the assistance are to be fulfilled at a time when in accordance with the agreement any obligation of another party to the agreement remains unfulfilled” (section 677(1)(c)(i)).
4. Using loan finance, the buyer acquires the target public company (which has a wholly owned subsidiary). The subsidiary is subsequently transferred to the buyer and the subsidiary grants security for the loan.
	1. The subsidiary of the target company is not giving financial assistance here if it is no longer a subsidiary of the target company.
	2. But the transfer of the subsidiary could constitute financial assistance if it was not made at market value.
5. Using loan finance, the buyer acquires shares in the target public company. The target subsequently acquires (or incorporates) a subsidiary which grants security for the loan.
	1. Although the subsidiary was not a subsidiary at the time of the acquisition, it is one at the time of the assistance (the security) is given and this will be caught by _[section 678(3)](https://uk.westlaw.com/5-505-7258?originationContext=document&transitionType=PLDocumentLink&contextData=(sc.Default)&ppcid=fc9f4d9e83af4b4c8d47bf5847a3205c)_.
6. A company borrows money, all or some of which it uses to subscribe for shares in a public company subsidiary. That subsidiary uses the money to acquire the majority of shares in the target public company. The subsidiary and target give guarantees and security for the bank borrowing.
	1. The guarantees and security granted by the target will constitute financial assistance for the acquisition of its shares.
	2. It will also constitute financial assistance for the acquisition of shares in its parent company (namely the subscription of shares in the subsidiary).
7. Using loan finance, the buyer acquires shares in the target public company. Subsequently, the buyer refinances this borrowing (that is, it borrows from a new lender and repays the original lender). This new borrowing is secured by the target company.
	1. The grant of security by the target company will constitute financial assistance within _[section 678(3)](https://uk.westlaw.com/5-505-7258?originationContext=document&transitionType=PLDocumentLink&contextData=(sc.Default)&ppcid=fc9f4d9e83af4b4c8d47bf5847a3205c)_ because its purpose is to assist in the discharge of a liability.
	2. However, if this new financing is subsequently itself refinanced (a second-round refinancing) security granted by the target company for that new lending will not be caught because that new lending is not discharging acquisition debt (but to discharge borrowings which themselves discharged acquisition debt).
8. Using loan finance, the buyer acquires shares in the target public company. Subsequently, the target company makes (otherwise lawful) dividend payments and loans to the buyer which the buyer uses to service or repay the loan.
	1. So far as the dividends are concerned, these fall within the unconditional exception in _[section 681(2)(a)](https://uk.westlaw.com/8-506-2055?originationContext=document&transitionType=PLDocumentLink&contextData=(sc.Default)&ppcid=fc9f4d9e83af4b4c8d47bf5847a3205c)_.
	2. However, the loans will be prohibited by _[section 678(3)](https://uk.westlaw.com/5-505-7258?originationContext=document&transitionType=PLDocumentLink&contextData=(sc.Default)&ppcid=fc9f4d9e83af4b4c8d47bf5847a3205c)_ and _[section 677(1)(c)](https://uk.westlaw.com/8-505-7474?originationContext=document&transitionType=PLDocumentLink&contextData=(sc.Default)&ppcid=fc9f4d9e83af4b4c8d47bf5847a3205c)_.

### Break Fees

Where the company whose shares are potentially being acquired pays the break fee (or agrees to do so) the break fee could amount to unlawful financial assistance. Draft such provisions carefully.

### Sanctions

#### Effect of Transaction

The transaction itself is illegal and unenforceable, as is any security or guarantee given in contravention of the prohibition. If a provision for illegal financial assistance is contained in a share purchase agreement, then it may be possible to sever the offending term.

#### Directors' Liability

If the provision of financial assistance is not in accordance with the directors' duty to act in the way they consider, in good faith, would be most likely to promote the success of the company for the benefit of its members as a whole (_[section 172](https://uk.westlaw.com/5-505-5377?originationContext=document&transitionType=PLDocumentLink&contextData=(sc.Default)&ppcid=fc9f4d9e83af4b4c8d47bf5847a3205c)_), and the breach has not been approved or ratified by an appropriate shareholder resolution the directors will be in breach of their duty and may have to account for any losses suffered by the company.

A director may also be liable for disqualification as a result of a company's involvement in a prohibited transaction (_[section 1](https://uk.westlaw.com/5-506-8501?originationContext=document&transitionType=PLDocumentLink&contextData=(sc.Default)&ppcid=fc9f4d9e83af4b4c8d47bf5847a3205c), [Company Directors Disqualification Act 1986](https://uk.westlaw.com/4-505-7796?originationContext=document&transitionType=PLDocumentLink&contextData=(sc.Default)&ppcid=fc9f4d9e83af4b4c8d47bf5847a3205c)_).

```ad-note
Misfeasance can include illegal financial assistance (s 212)
```

#### Recipient Liability

If a person receives money from a company as a result of illegal financial assistance and knew or ought to have known of the circumstances rendering the assistance illegal, then a constructive trust may arise in favour of the company (_[Belmont Finance Corp Ltd v Williams Furniture Ltd (No 2) [1980] 1 All ER 393](https://uk.westlaw.com/D-016-7350?originationContext=document&transitionType=PLDocumentLink&contextData=(sc.Default)&ppcid=fc9f4d9e83af4b4c8d47bf5847a3205c)_). The third party may be required to account for any money or property received in breach of _[section 678](https://uk.westlaw.com/5-505-7258?originationContext=document&transitionType=PLDocumentLink&contextData=(sc.Default)&ppcid=fc9f4d9e83af4b4c8d47bf5847a3205c)_ or _[679](https://uk.westlaw.com/6-506-2056?originationContext=document&transitionType=PLDocumentLink&contextData=(sc.Default)&ppcid=fc9f4d9e83af4b4c8d47bf5847a3205c)_ as a constructive trustee.

#### Restrictions on Relevant Shares

A person who has been given illegal financial assistance by a public company to acquire that company's shares and who holds those shares as a trustee for the company must not exercise any voting rights attached to the shares (_[section 662(1)(e)](https://uk.westlaw.com/5-506-0543?originationContext=document&transitionType=PLDocumentLink&contextData=(sc.Default)&ppcid=fc9f4d9e83af4b4c8d47bf5847a3205c)_).

#### Criminal Sanctions

The only sanction set out in the _[CA 2006](https://uk.westlaw.com/3-503-8567?originationContext=document&transitionType=PLDocumentLink&contextData=(sc.Default)&ppcid=fc9f4d9e83af4b4c8d47bf5847a3205c)_ provides that contravention of _[section 678(1) or (3)](https://uk.westlaw.com/5-505-7258?originationContext=document&transitionType=PLDocumentLink&contextData=(sc.Default)&ppcid=fc9f4d9e83af4b4c8d47bf5847a3205c)_ or _[section 679(1) or (3)](https://uk.westlaw.com/6-506-2056?originationContext=document&transitionType=PLDocumentLink&contextData=(sc.Default)&ppcid=fc9f4d9e83af4b4c8d47bf5847a3205c)_ renders the company liable to a fine and every officer in default liable to a fine or up to two years' imprisonment or both (_[section 680](https://uk.westlaw.com/4-506-2057?originationContext=document&transitionType=PLDocumentLink&contextData=(sc.Default)&ppcid=fc9f4d9e83af4b4c8d47bf5847a3205c)_).

“Officers” include directors, managers and secretaries and any person who is to be treated as an officer of the company for the purposes of the provision in question (_[section 1121(2)](https://uk.westlaw.com/2-506-8531?originationContext=document&transitionType=PLDocumentLink&contextData=(sc.Default)&ppcid=fc9f4d9e83af4b4c8d47bf5847a3205c)_). Officers who may be liable are those who authorise or permit, participate in, or fail to take all reasonable steps to prevent the contravention (_section 1121(3)_).

## Applicable Law

### Security Interests

The legal system which governs a security interest will dictate how the security will be perfected (eg, notice, registration, etc) and how it may be enforced.

| Type of asset             | Legal system                                                                                                                                                                                                                                                      |
| ------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Immovable assets          | Security governed by the legal system of the place where the assets are physically situated (known as the ‘_lex situs_’).                                                                                                                                         |
| Tangible movable assets   | Generally, the _lex situs_ of the asset when the security is created will determine the validity of its creation and perfection. Generally, the _lex situs_ of the asset when the security is created will determine the validity of its creation and perfection. |
| Intangible movable assets | Security over intangible assets (eg, debts) is usually subject to the governing law of the contract creating the asset, but the law of the place of performance of the asset (eg, where the debt is to be paid) is also relevant.                                                                                                                                                                                                                                                                  |

### Insolvency

From 31 May 2002, the EU Insolvency Regulation (EUIR) came into force in all EU Member States except Denmark. The EUIR provides rules that dictate which system of insolvency law applies in a ‘cross-border’ insolvency situation.

- Under the EUIR, the main insolvency proceedings will be opened in the jurisdiction of the entity’s Centre of Main Interest (COMI).
- There is a rebuttable presumption that the COMI is in the jurisdiction of an entity’s registered office (Article 3(1)), although factors such as location of employees, head office, board meetings and where the company does most of its business can influence the COMI.
- 2 main circumstances in which assets may be subject to insolvency proceedings in jurisdictions other than the COMI.
	1. Assets outside the COMI which are subject to ‘rights in rem’ are basically unaffected by the COMI proceedings.
	2. Supplemental proceedings may be brought in a jurisdiction where a company has an ‘establishment’.
- The EUIR applies to companies, partnerships and individuals with their COMI in an EU Member State (other than Denmark), but not to most regulated entities (eg, banks, insurance companies) which have separate regimes.
- The UK now has a slightly different regime but the EUIR largely operates unchanged.

## UNCITRAL Model Law

Cross-Border Insolvency Regulations 2006 implements the main provisions of the ‘Model Law’ on Cross-Border Insolvency devised by UNCITRAL (the United Nations Commission on International Trade Law). EUIR takes precedence where there is a clash.

## To Consider

When advising on security issues, also consider:

- Prior security
	- Check for negative pledges
	- May need a subordination agreement.
- Notification requirements
	- May need to notify third parties like licensing authorities and landlords.
- Overseas registration.
	- Security interests over overseas properties may need registering in the jurisdiction in which situated.
- Parallel debt structures
	- Security for a syndicated loan will be held by a security trustee (usually one of the lenders): legal title to the security is held on trust and the syndicate banks are the beneficiaries.
	- This allows syndicate members to change without danger of the security being treated as renewed (losing priority/ hardening periods).
	- Trusts aren't a thing in civil law jurisdictions, so a "parallel debt" structure may be used instead.
		- A security agent holds the security on behalf of the syndicate.
		- But most jurisdictions only allow a party to hold security to the extent it is owed a debt.
		- Parallel debt structure creates a debt owed to the security agent in the same amount as the debt owed to the bank syndicate.
		- Normally, if the borrower repays the syndicate, any amount it repays is deemed to reduce the syndicate debt by the same ("in parallel").
		- On a default, however, the security agent becomes entitled to demand repayment of the debt owed to it and enforce the security if necessary. For every amount the security agent recovers, the syndicated debt will be deemed to reduce by the same.
		- Not as good as a trust; the syndicate takes a risk on the security agent becoming insolvent.

# Debentures

The document creating multiple security interests (e.g. charges, mortgages, assignments) for a secured loan is commonly known as a ‘debenture’.

## Structure

- Most banks have their own short standard form security agreement.
- More sophisticated secured loans require a bespoke debenture drafted by the bank's solicitor.
- The broad structure of most debentures is similar to other commercial documents, ie: date, title and parties; preamble; definitions; operative provisions; schedules; and execution.

Operative provisions:

### Covenant to Pay

- Acknowledges the debt obligation of the borrower to the bank, and may refer to a specific debt obligation/ to all the debts between the bank and borrower (“all monies” clause).
- Purposes:
	1. Brings the document within the common law definition of debenture – ‘a document which either creates a debt or acknowledges it’ ([[Levy v Abercorris Slate and Slab Co (1887) 37 Ch D 260]]). Satisfies one of the conditions to appointing an administrative receiver under s 29(2) IA 1986.
	2. In a syndicated loan, the covenant to pay is addressed to the security trustee (“Security Agent”). Allows the security trustee to demand repayment and enforce security on behalf of the syndicate members.
- “On demand” intended to prevent Limitation Act 1939 from acting against the bank until it makes a demand.
	- It does not alter the payment obligation in a facility agreement which it secures.
	- Some debentures refer to monies owing or incurred ‘on any account whatsoever’, but this wording may be inadvisable because there is a danger that it would not include certain types of obligation ([[Re Quest Cae Limited [1985] BCLC 266]])

### Charging Clause

Specifies which of the borrower's assets are charged to repay the debts acknowledged in the covenant to pay, as well as how each type of asset is secured.

#### Land

- A debenture will usually secure leasehold and freehold land by way of a ‘charge by way of legal mortgage’.
- Details of registered land to be secured included in a schedule to the debenture so the security can be registered at the Land Registry.
- Check the terms of any leases to ensure they do not prohibit granting of security interest.
- Future acquired land cannot be secured by legal mortgage, and is therefore secured by a separate equitable mortgage or charge over the property as soon as it is acquired.
	- The borrower may then be required subsequently to ‘upgrade’ this to a legal mortgage.

#### Fixed Plant and Machinery

- A mortgage of land will automatically secure any assets which are, or become, permanently fixed to the secured property (known as ‘fixtures’).
- May be other assets which are not fixtures but are fixed assets.

#### Cash Deposits

 A bank may want to take security over a cash deposit made with it (e.g., if it has provided a performance guarantee).

##### Mortgage/ Charge

 The obvious way to secure the account is for the depositor to create a mortgage or charge over it in favour of the bank. But in [[Re Charge Card Services [1987] Ch 150]],

> [a debt] … cannot be made the subject of a legal or equitable mortgage in favour of the debtor, since this requires a conveyance or assignment by way of security, and this operates as a conditional release;

and

> A charge in favour of a debtor of his own indebtedness to the chargor is conceptually impossible.

```ad-note
title: Logic
- An account is a debt owed by a bank to a depositor. 
- A debt is a right to sue the debtor for the amount owed. 
- If this was charged/ mortgaged in favour of the debt, this would give the debtor the right to sue itself. 
- So this would cancel/ reduce the debt. 
```

In [[Morris v Agrichemicals Ltd [1997] 3 WLR 909]] (‘BCCI No 8’), the House of Lords, led by Lord Hoffmann, declared that a **charge** in favour of a person over the benefit of a deposit made with that person, by another, is not a conceptual impossibility. But an assignment (mortgage) of the account to the bank remains ineffective.

```ad-question
How shold a depositor provide a bank with security ("cash collateral") over a deposit with that bank?
```

The means of enforcing a cash collateral arrangement should be by set-off – contractual set-off prior to winding-up, and mandatory set-off after winding-up. Any security granted over the account is intended to ensure that the money is in the account when the bank needs to set off. So the bank should require:

1. An express contractual right of set-off;
2. a fixed charge over the account (assuming the depositor will not be allowed to withdraw any money without the bank’s prior consent);
3. a prohibition on the depositor assigning the account (to deal with the fact that a bona fide purchaser, for value, without notice could defeat the fixed charge); and
4. if the depositor’s obligation is contingent, a ‘flawed asset’ arrangement (that is, the deposit only becomes repayable at the same time that the depositor’s debt becomes due and unpaid). This protects the account from a liquidator until the bank can exercise its rights of set-off.

```ad-note
- An assignment (mortgage) will usually be possible if security over an account is given to a security trustee or an agent bank on behalf of a syndicate
- None of these issues will apply if a borrower gives security over an account held with a third party bank.
```

#### Goodwill

Any goodwill held by a borrower is probably automatically secured as an inseparable part of the borrower’s secured ‘undertaking’. But usually the debenture explicitly secures the borrower's goodwill by fixed charge.

#### Book Debts

Book debt is an unpaid invoice, i.e., a sum owed to the company in respect of goods or services supplied by it.

Book debts (or “receivables”) are a fluctuating asset, and may be a significant asset of the company.

In early cases, the courts took the approach that a charge granted over book debts was a fixed charge, but this approach has now been overruled.

Case | Authority
---|---
[[Siebe Gorman and Co Ltd v Barclays Bank Ltd [1979] 2 Lloyd's Rep 142]] | The court held that a charge over book debts was a fixed charge because of the degree of control of the bank which could stop the company making withdrawals, even when the account was in credit. Since overruled.
[[Re Brightlife Ltd [1987] Ch 200 ChD]] | The court in this case clarified that a company's bank balance is not a book debt and therefore cannot be subject to a fixed charge.
[[Re Keenan Bros Ltd [1986] BCLC 242]] | A fixed charge was created by the means of a requirement that the funds collected by the company were to be paid into a blocked account. The prior written consent of the bank was required before any funds were allowed to be withdrawn from this account. Here the court said that the charge was a fixed charge due to the fact that the account was blocked.
[[Re Brumark Investments Ltd [2001] ]] | The company's freedom to collect and use the proceeds of the book debts as it wished without requiring the lender's consent was inconsistent with the nature of a fixed charge. This was a Privy Council case, which means that it is persuasive but not binding.

Most cases suggest that **book debts have two elements, the debt and the proceeds of the debt**, and that a bank must show control over both elements to achieve fixed security over either. Taking control over the debt element is usually uncontroversial: the bank must prevent the borrower doing anything other than collecting in the debt. Controlling the proceeds is more difficult, because the borrower usually needs access to them to run its business.

In the early 1990s there was a run of judgments which moved against the previous cases and was much more in favour of the banks. The leading case was [[Re New Bullas Trading [1994] 1 BCLC 485]], where the Court of Appeal blessed a debenture allowing fixed security over the unrealised debt and floating security over the proceeds. But this was subject to lots of criticism.

Eventually, the position was resolved in [[National Westminster Bank plc v Spectrum Plus Limited and others [2005] UKHL 41]]. It is now very difficult to demonstrate the requisite level of control over book debts for a fixed charge. It would require at least a blocked account.

```ad-important
title: Charge over book debts

From the case of [[National Westminster Bank plc v Spectrum Plus Limited and others [2005] UKHL 41]] it is only possible to have a fixed charge over book debts if they are paid into a blocked account which gives the lender the degree of control required.

**Book debts can only be secured by a fixed charge where the charge holder has control over both the debts and the proceeds once they were paid.**
```

The vexed question for practitioners, still unanswered by the courts, is how much control (if any) may be given to the borrower without fixed security being lost.

The court will look at the substance of an arrangement, not the title.

#### Shares

Shares may be in

- Registered form (in which a register of legal owners is maintained by the company),
- Bearer form (where legal ownership is generally determined by possession of the share certificate) or
- ‘Dematerialised’ (where they are held and traded electronically).

Registered shares usually secured by either:

1. Creating a legal mortgage by transferring the shares into the bank’s name and issuing a new share certificate to that effect.
	- Rare – lots of admin and potential liabilities for the bank.
	- [[Enviroco Ltd v Farstad Supply A/S [2009] EWCA Civ 1399]]: a company ceases to be a subsidiary of its holding company if the holding company gives a legal mortgage over the subsidiary’s shares.
	- The debenture will allow the bank to sell the shares on default of the borrower and provide for re-transfer when the loan is repaid.
2. Creating an equitable mortgage (or charge) by taking custody of the share certificate together with a stock transfer form executed by the borrower, but with the transferee’s name and other details left blank.
	- The security document should also contain a power of attorney allowing the bank to complete the stock transfer form and submit it, with the share certificates, to register a new owner.
	- The bank does not have the ‘inconvenience’ of ownership pre-enforcement (e.g., voting, passing dividend back to the borrower) and does not run the risk of the company whose shares are secured becoming a subsidiary of the bank.

The bank’s solicitor should ensure:

- that the shares are fully paid up,
- that (for (1)) any stamp duty payable on the transfer form has been paid, and
- that there are no restrictions on transfer in the articles (e.g., pre-emption rights).

In the case of bearer shares, security is usually achieved simply by taking delivery of the share certificate and a memorandum of deposit (i.e., a pledge).

#### Stock in Trade and Sundry Assets

A borrower’s stock, sometimes known as ‘inventory’, is by definition an asset the borrower needs to sell and so will typically be secured by a floating charge.

#### Contracts

Contractual rights are choses in action and so may be secured by way of assignment (legal or equitable) or a charge. Which of these security devices is used will depend on a number of factors, including whether:

- the contract is specified as ‘non-transferable’;
- the borrower needs to alter the contract from time to time;
- it is preferable for the borrower to enforce the contact rights;
 - all or only part of the contract is to be secured;
 - the counterparty can be notified; and
 - the contract has specific features (e.g. an insurance contract).

### Further Assurance Clause

```ad-defn
title: Further assurance
An undertaking by the borrower to do anything necessary in order to perfect the security.
```

May include execution of documents, conversion of an equitable to legal mortgage, deposit of documents of title or provision of additional security.

### Undertakings

Most debentures contain undertakings. The most common are:

- A negative pledge
	- Often included even if the facility agreement contains a negative pledge to help ensure registration at Companies House.
- Undertaking to execute, at the bank’s request, a legal mortgage in place of an equitable one;
- an undertaking to provide the bank with any documents of title it might request;
- an undertaking to repair and maintain land, and insure all assets, together with a power of attorney allowing the bank to do these things (and recover any expenses it incurs) if the borrower does not.

### Crystallisation Clause

If it creates a floating charge, the debenture will specify when the floating charge crystallises. Usually:

1. At any time, the bank notifies the borrower in writing (though the borrower may resist this and insist on default/ perceived risk)
2. Automatically on specified events (e.g., any demand for repayment, on a petition for winding-up etc.)

### Enforcement

The bank will have a right (subject to contrary agreement) to immediate possession of any assets over which it has a legal mortgage, but not those over which it has an equitable mortgage/ charge.

The debenture should therefore give the bank

- an express contractual right to take possession of the charged assets on specified ‘enforcement events’ (i.e., events of default).
- enhanced powers to sell, lease and appropriate secured assets on enforcement.
- the right, on an enforcement event, to appoint a receiver of the secured property, an administrator and, if permitted, an administrative receiver. Such appointees will be extended any enhanced rights given to the bank.

### Collection of Debts

A debenture will usually require the borrower to collect in any debts and claims of the business ‘promptly’, and to pay them into specified accounts.

### Power of Attorney

A debenture will invariably provide the bank and any receiver it appoints with a power of attorney.

- This will allow the bank to carry out any of the borrower’s obligations under the debenture which the borrower fails to honour.
- Also assists in enforcement of security.
- The instrument creating a power of attorney must be executed as a deed and, provided it is given to secure a proprietary interest of the donee and also expressed to be ‘irrevocable’, it will survive the borrower’s liquidation (Powers of Attorney Act 1971, s 4).

### Redemption of Security

The debenture must provide for the release of the security once the secured obligations are satisfied.

The debenture may allow the bank, if it believes a preference (or similar) claim is possible, to deem the debt and related security to ‘continue’ even after repayment. Unproven and probably not workable.

There are no strict formalities for the discharge of security, other than for registered land.

### Administrative Provisions

A debenture will contain a number of boilerplate clauses concerning administrative matters, such as notice periods, interpretation, service of documents, and costs and expenses.

## Execution

Debentures should be made by deed:

1. it avoids any doubt as to sufficiency of consideration;
2. it is necessary because debentures invariably create a power of attorney (see the Power of Attorney Act 1971, s 1);
3. it is necessary if a debenture conveys or creates a legal estate in land (LPA 1925, s 52); and
4. it is necessary if the bank is to take powers under LPA 1925, s 101 (powers of mortgagees to sell mortgaged property/ enter into contracts etc.).

A debenture should also be expressed as being made by the borrower ‘in favour of the bank’ (rather than ‘between’ borrower and bank) to ensure that it can be enforced by a party other than the bank (e.g., a receiver or attorney).

# Legal Opinions

First introduced in US, now usual for UK banks making substantial loans or capital market investments.

## Fundamentals

### Purpose

Relate only to matters of law. In banking, a legal opinion will usually confirm that all the documents associated with the loan are legally valid and enforceable and highlight areas of risk.

### Who

Typically provided by the bank's solicitor, addressed to the bank. Generally, only an addressee may sue the solicitor if the opinion proves wrong, although the solicitor will owe a general responsibility to anyone they know has relied on their advice. If the transaction involves a syndicate (or underwriters), the opinion may be addressed to the agent bank on their behalf, or be addressed to each of them individually.

### When

Almost always required for:

| Scenario               | Details                                                                                        |
| ---------------------- | ---------------------------------------------------------------------------------------------- |
| Large loans            | Opinion by the bank's lawyers that the documents are legal, valid and binding.                 |
| Secured lending        | Statement confirming the priority and enforceability of the security and to outline any risks. |
| Overseas jurisdictions | Legal opinion required by a local lawyer.                                                                                                |

- Even if the loan is a repeat of an earlier one (a re-financing), the bank may still require a new opinion (to update effect).
- A bank will usually make the delivery of a satisfactory legal opinion a condition precedent to the loan being drawn down.
	- A borrower ideally should insist that the bank and the opining solicitors agree the form of the opinion in advance of executing the facility agreement.

### Form

Written as a letter on the solicitor's headed notepaper, addressed to the bank and signed in the firm's name.

Structure:

1. Preamble;
2. assumptions;
3. opinion; and
4. qualifications.

## Preamble

- Outlines form of loan transaction
- Lists all the documents in respect of which the opinion is given
- Lists specific documents which the solicitor has reviewed in order to give the opinion.
- Usually delivered after the documents to which it refers have been executed – if not be clear that it refers to a particular draft.
- Record of any searches on which the opinion relies and the date on which they were done.

## Assumptions

- All signatures appearing on reviewed documents are genuine
- Documents submitted to the solicitors as originals are authentic and complete
- All copies complete and accurate.
- Any resolutions properly passed at quorate meetings duly held
- Documents accurate
- Draft documents executed unchanged
- Searches remain unchanged
- No insolvencies since the opinion
- No foreign law affects the conclusion
- That the bank had no notice of any prohibition or restriction on creating the security, or notice of any other security in the same assets;
- that immediately after providing any guarantee (or other security), each obligor was fully solvent, and that the provision of the guarantee (or security) was in good faith, for the benefit of the obligor and did not constitute financial assistance.

## Opinion

- Actual opinion appears in the form of numbered statements.
- Short compared to the overall length of the letter.
- The exact form of legal opinion will be negotiated between bank and solicitor.

Commonly includes:

- That borrower was properly incorporated and not in liquidation.
- Borrower has requisite power to enter into and perform the facility agreement, and has taken action necessary to authorise execution.
- Execution, delivery and performance will not contravene English law or regulation, and will not violate memorandum/ articles.
- Payments made by the borrower not subject to UK taxes and no taxes payable on execution/ registration of facility agreement.
- All necessary registration, filings, licences and consents have been obtained in order to validate the loan document.

## Qualifications

Commonly:

- The validity, performance and enforcement of the facility agreement may be affected by insolvency proceedings.
- Any declaration in the opinion that the facility agreement is enforceable must be read on the basis that equitable remedies are at the discretion of the court
- A provision purporting to create a fixed charge may be construed as creating a floating charge
- The enforcement of some security rights is controlled by law.
- Any claims under the loan may be affected by lapse of time.
- The opinion can only take account of the law of England and Wales.
- A court may refuse to entertain proceedings if a claim has been, or is being, brought elsewhere.
- Certain specific provisions may not be upheld by a court, most notably default interest, provisions for severability, and provisions requiring a borrower to pay the costs of litigation on enforcement.

## Foreign Counsel Legal Opinions

If the facility agreement is governed by English law but a borrower (or guarantor) is incorporated outside of England and Wales, the banks will usually require a legal opinion from counsel in that jurisdiction.

This should cover:

- Borrower's status (duly incorporated etc.)
- Borrower has power and authority to execute transaction and perform obligations
- No legal conflict (with law or constitution of the borrower).
- Legal, valid, binding and enforceable
- Filings, registrations and consent – confirmation that no further action is needed (e.g., executing in front of a notary, which is common under civil law).
- Withholding tax – lenders sensitive to withholding tax being imposed.
- Domicile – confirmation that the lenders will not become domiciled in the local jurisdiction by virtue of the transaction documentation.
- Choice of law – confirmation that it will be recognised.
- Lender's claim to rank _pari passu_ (at least)
- Jurisdiction and agent for service of process.
	- Confirmation that the borrower’s submission to jurisdiction is valid and cannot be revoked.
	- Confirmation that the appointment of an agent in the jurisdiction of the governing law (an ‘agent for service of process’) is valid and cannot be revoked.
- Validity of security and that it covers future as well current advances.

Other issues:

- No limitation on paying interest
- No exchange control
- Borrower solvent
- Borrower cannot claim immunity to proceedings.
- Whether there are any restrictions on providing guarantees and security.
- Whether there are issues with financial assistances.

## Reference in Facility Agreement

```ad-warning
The legal opinion is likely to be referred to in the “Representations” section of the facility agreement and is likely to be listed as a “Condition Precedent” in the facility agreement.
```
