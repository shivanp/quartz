---
aliases: 
tags: 
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
  - color: blue
    classes: [admonition, admonition-note]
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
date created: Saturday, September 10th 2022, 10:33:20 pm
date modified: Sunday, December 10th 2023, 12:39:48 am
---

```toc
min_depth: 1
```

# Inheritance Tax

## Introduction

Usually a solicitor does the tax calculations for inheritance tax (accountants do income and capital gains tax). It has not kept pace with inflation, so has in practice become a tax on the middle classes. Levied on wealth at death. Governed principally by **Inheritance Tax Act 1984 (IHTA 1984)**. Charged on 3 main occasions:

1. Death
2. Lifetime gifts made by individuals within 7 years of death
	- Such gifts known as 'potentially exempt transfers' (PETs)
	- If transferor survives for 7 years, becomes exempt.
	- If transferor dies within 7 years, becomes chargeable.
3. Lifetime gifts to a company or into a trust.
	- Such lifetime gifts are immediately chargeable to IHT at the time when it is made, unless the trust is for a disabled person.

IHT subject to 'general anti-abuse rule' (GAAR) introduced by Finance Act 2013 designed to allow HMRC to counteract abusive tax avoidance schemes.

## Calculation

1. Identify the transfer of value
	- Must have been a transfer of value. This is a disposition which reduces the value of the transferor's estate. Basically, there must have been a gift.
	- You are deemed to have made a gift when you die. So death is a deemed transfer of value.
	- Death estate: all the assets to which the deceased was beneficially entitled immediately before death.
2. Find the value transferred.
	- Upon death, value transferred is market value less debts and funeral expenses.
	- For a lifetime transfer, it is the amount of the reduction in the transferor's estate.
3. Apply exemptions and reliefs.
	- Depends on status of person to whom assets are transferred, or nature of assets.
	- Spouse exemption: full exemption between spouses.
	- Charity exemption
	- Business and agricultural property relief
	- Annual exemption
		- £3,000
		- Applies only to lifetime transfers.
4. Calculate tax at appropriate rate
	- Residence nil rate band
		- Must be a “qualifying residential interest”
		- “Closely inherited”–lineal descendants
		- First £175,000 taxed at 0%
		- Only available on death
	- Nil rate band
		- £325,000 taxed at 0%
		- Complicated by cumulation–relates to the nil rate band
		- Can be passed onto spouse/ civil partner.
	- So potentially £1 million taxed at 0%.

Chargeable transfers eat up the nil rate band.

```ad-warning
It is not correct to say that the property falling into the nil rate band is "exempt". When something is exempt it has no IHT implications.
```

## Transfers on Death

### 1. Transfer of Value

The value transferred is the value of the deceased's estate immediately before death.

#### Estate

Defined in s 5(1) IHTA 1984 to mean all the property to which a person was beneficially entitled immediately before their death, with the exception of ‘excluded property’. So it includes:

- Property passing under will/ intestacy
	- Deceased “beneficially entitled” to all such property immediately before death.
- Other property to which the deceased was beneficially entitled immediately before their death.  
	- Interest in any joint property passing on death by survivorship to surviving joint tenants.
- Property included because of special statutory provisions.
	- Certain trust properties
		- In certain circumstances, a person entitled to the income from a trust is treated for IHT purposes as beneficially entitled to the capital which produces that income.
		- Known as a “qualifying interest in possession”.
		- Interest in possession: fixed trust where beneficiary is entitled to income.
		- An interest in possession arising **before** 22 March 2006 will be a qualifying interest in possession.
		- After this, more limited circumstances: e.g., being an 'immediate post-death interest'
	- Property given away during lifetime 'subject to a reservation'.
		- Applies where deceased gave away property during their lifetime but did not transfer possession and enjoyment of the property to the donee.
		- Donor treated as being beneficially entitled to the property.

But does not include:

- Property outside the estate
	- Life assurance policy once it is written in trust for a named beneficiary.
	- Discretionary lump sum payment made from a pension fund to the deceased's family.
- Excluded property
	- e.g., 'reversionary interest': interest in remainder under a trust.

### 2. Value Transferred

```ad-guid
title: General principle - s 160 IHTA 1984
Assets are valued for IHT pruposes at 'the price which the property might reasonably be expected to fetch if sold on open market' **immediately before** death.
```

With assets such as land, may need negotiations with the district valuer to reach an agreed valuation.

```ad-defn
The value of an asset agreed for IHT purposes is known as the **probate value**.
```

Where death causes the value of an asset to increase or decrease, this will be taken into account (important for e.g., life insurance policies).

| Asset              | How to value                                                                                                                           |
| ------------------ | -------------------------------------------------------------------------------------------------------------------------------------- |
| Quoted [[Shares]]  | Value taken from Stock Exchange Daily Official List for date of death. $\text{Value} = \text{bid} + \frac{1}{4}\left( \text{bid-ask spread}\right)$ |
| Debts and expenses | Debts/ expenses at time of death deductible provided incurred for money/ money's worth (s 505 IHTA 1984). Reasonable funeral expenses deductible (s 162 IHTA 1984).                                                                                                                                        |

### 3. Exemptions/ Reliefs

#### Spouse/ Civil Partner Exemption

```ad-statute
title: s 18 IHTA 1984
A transfer of value is an exempt transfer to the extent that the value transferred is attributable to property which becomes comprised in the estate of the transferor’s spouse or civil partner.
```

The spouse exemption can apply in conjunction with the rule applicable to qualifying interest in possession trusts, that IHT is charged as if the person with the right to income owned the capital. So if a trust is validly created with income for life for a spouse, remainder to children, the whole estate will be spouse exempt on the settlor's death.

#### Charity Exemption

```ad-statute
title: s 23(1) IHTA 1984
Transfers of value are exempt to the extent that the values transferred by them are attributable to property which is given to charities.
```

A similar exemption applies to gifts to certain bodies, bodies providing a public benefit, and to political parties.

#### Business Property Relief

Provided that the transferor owned the property/ a replacement property for **2 years** immediately before the transfer, there is a 100% reduction for:

- A business or interest in a business (including [[Business Law and Practice/Company Law/Business models/Partnership]] share), and
- Company shares not listed on a recognised stock exchange
	- AIM not included in definition of recognised stock exchange.

And a 50% reduction for:

- Quoted shares giving the transferor voting control of the company, and
	- Voting control means the ability to exercise $>50\%$ votes on all resolutions. So this can be denied by *Bushell v Faith* clauses.
	- Separate shareholdings of spouses/ civil partners sometimes taken into account.
- Land, buildings and machinery owned by the transferor personally but used for business purposes by a partnership of which the transferor is a member, or by a company of which the transferor has voting control.
	- Note that partnerships treated more favourably than companies here.

Where there is a lifetime transfer followed by the death of the transferor within 7 years, BPR given at the time of the lifetime transfer will be withdrawn unless the transferee still owns the business property at the date of the transferor's death.

Note:

- Transfer need not be of the entire interest/ shareholding.
- Where a person has entered into a contract for sale of their interest in a business, their interest is then taken to be in the proceeds of sale. Cash is not a relevant business property, so no relief available.

#### Agricultural Property Relief

The relief operates to reduce the agricultural value of agricultural property by a certain percentage.

```ad-defn
title: Agricultural value
The value of the property if it were subject to a perpetual covenant prohibiting its use other than for agriculture. 
```

Reduction of 100% is allowed where:

- The transferor had the right to vacant possession immediately before the transfer, or
- Where the property was subject to a letting commencing on/ after 01/09/1995.

Reduction of 50% allowed in other cases.

Must also have been occupied by transferor for 2 years prior to transfer/ owned by them for 7 years prior to transfer and occupied throughout for the purpose of agriculture. Also applies when there is a company structure in the way, of which the transferor had voting control.

Agricultural property relief given in priority to business property relief.

### 4. Calculate Tax

- 0% on first £325,000
- 40% on anything higher
- If $\geq 10\%$ of a defined 'component' of a person's net estate passes to charity, 36% rate applies instead of 40%.

#### Cumulation

Any chargeable transfers made by the transferor over the 7 years before the transfer must be taken into account to determine how much of the nil rate band remains available. Any lifetime exemptions are taken into account.

Not applicable to the residence nil rate band which should be available in full on death, subject to any adjustments for estates over £2 million.

#### Residence Nil Rate Band

| Tax year        | Rate         |
|:--------------- |:-------- |
| 2017/18         | £100,000 |
| 2018/19         | £125,000 |
| 2019/20         | £150,000 |
| 2020/21 onwards | £175,000 |

##### Conditions

This is available in addition to the nil rate band if the deceased dies owning a 'qualifying residential interest' which is 'closely inherited'.

```ad-defn
title: Qualifying residential interest
An interest in a dwelling house which has at any time been the deceased’s residence and which forms part of the deceased’s estate.
```

For a property to be **‘closely inherited’**, it must pass to:

1. a child, grandchild or other **lineal descendant** of the deceased outright or on certain types of trust. Lineal descendants are defined as children, step-children, adopted children, foster children, or children where the deceased had been appointed as a guardian;
2. the current spouse or civil partner of the deceased’s lineal descendants; or
3. the widow, widower or surviving civil partner of a lineal descendant who predeceased the deceased, unless such persons have remarried or formed a new civil partnership before the deceased’s death.

Only applies up to the value of the deceased's residence. If estate worth $\geq £2,000,000$, RNRB reduced by £1 for every £2 over £2 million threshold.

##### Downsizing

Finance Bill 2016 introduced a downsizing allowance; allowing PRs to claim RNRB to which the deceased would have been entitled, had they held onto their property, but instead moved to a care home etc.

## Potentially Exempt Transfers (PETs)

```ad-defn
title: PET
Any gift made by an individual to another **individual or into a disabled trust** (IHTA 1984, s 3A(1A)), to the extent in either case that the gift would otherwise be chargeable.
```

### 1. Transfer of Value

```ad-defn
title: Transfer of value
Any lifetime disposition made by the transferor which reduces the value of their estate (s 3(1) IHTA 1984)
```

Some dispositions are excluded:

- Maintenance, education or training of transferor's child under 18/ adult in full time education
- Maintenance of a dependent relative (s 11 IHTA 1984).

### 2. Value Transferred

```ad-defn
title: Value transferred
The amount by which the value of the transferor's estate is less than it would have been but for the transfer (s 3(1) IHTA 1984). 
```

Recall, the transferor's **estate** is the aggregate of all the property to which they are beneficially entitled.

#### Related Property

Designed to prevent tax avoidance in relation to a group of assets. The value of a single asset within a group of similar assets is the appropriate fraction of the total collection of assets if higher, rather than the value of the single item.

### 3. Exemptions and Reliefs

A gift is potentially exempt only to the extent that it would otherwise be chargeable.

#### Standard Exemptions

The usual exemptions/ reliefs apply:

- Spouse/ civil partner exemption
- Charity exemption
- Business and agricultural property relief.
	- Only available if transferee still owns the property or qualifying replacement when transferor dies.

```ad-test
title: Order of application
Apply exemptions and reliefs in the following order:
1. Spouse/ civil partner/ charity exemptions
2. Business/ agricultural property reliefs
3. 'Lifetime only' exemptions
```

#### Lifetime Exemptions

| IHTA 1984 | Exemption                        | Details                                                                                                                                                                                                                                                                                                         |
| --------- | -------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| s 19      | Annual exemption                 | The annual exemption applies to the **first** £3,000 transferred by lifetime transfers in each tax year. This can be carried forward for one year–but current year's exemption must be used before previous year's can be carried forward. So there is a total annual exemption for any given year of £6,000. |
| s 20      | Small gifts                      | Lifetime gifts in any tax year of £250 or less to any one person are exempt. Exemption cannot be set against a gift exceeding £250.                                                                                                                                                                             |
| s 21      | Normal expenditure out of income | Lifetime transfer exempt if: (1) Made out of transferor's normal expenditure; (2) Made out of transferor's income; and (3) After allowing for such payments, transferor was left with sufficient income to maintain usual standard of living.                                                                   |
| s 21      | Marriage consideration           | Lifetime gifts on marriage are exempt up to: £5,000 by a parent of a party to the marriage; £2,500 by a remoter ancestor of a party to the marriage (eg, a grandparent); and  £1,000 in any other case.                                                                                                         |

#### Potentially Exempt

Any value remaining after exemptions and reliefs applied is potentially exempt. Transfer becomes chargeable only if transferor dies within 7 years.

## Lifetime Chargeable Transfers (LCTs)

```ad-note
An LCT is made to a company or trust. 
```

Any lifetime transfer which does not fall within the definition of a PET is an LCT. The aim is to close loopholes involving companies and trusts.

Main examples:

- Lifetime transfer made on or after 22/03/06 into any trust (other than a disabled trust)
- Lifetime trust into a discretionary trust or company.

### 4. Calculate Tax

First identify transfer of value, calculate value transferred and apply exemptions and reliefs, as set out in (1) to (3) above. Then apply rates:

- 0% on first £325,000 (nil rate band)
- 20% on the balance of the chargeable transfer.

#### Cumulation

```ad-important
Chargeable transfers made in the 7 years before the current chargeable transfer reduce the nil rate band available to that current transfer. 
```

Note that while the transferor is alive, any PETs made by the transferor are ignored for cumulation purposes because they may never become chargeable.

## Effect of Death on Lifetime Transfers

The death of a transferor may result in a charge /additional charge to IHT on any transfers of value which they have made in the 7 years immediately preceding death, whether these were PETs or LCTs.

- PETs made become chargeable and the transferee becomes liable for any IHT payable.
- IHT liability on LCTs is recalculated, and trustees will be liable for any extra tax payable.

Work chronologically forwards over 7 years, calculating appropriate tax.

### 4. Effect on PETs

Apply steps (1) to (3) to determine size of PET. Then establish the transferor's cumulative total of transfers at the time of the PET. Made up of:

1. Any LCT's made in 7 years before the PET, and
2. Any other PETs made during the 7 years before the PET being assessed.

Rate of tax applicable to **chargeable transfers** made within 7 years of death are:

- 0% on available nil rate band
- 40% on balance (note 36% charity rate not available).
- But subject to tapering relief, see below.

```ad-tip
Draw a timeline. 
```

#### Tapering Relief

When a PET becomes chargeable, tapering relief is available if transferor survives $>3$ years after transfer. Any tax payable on PET is reduced.

| Years between PET and death | Tax rate |
|:--------------------------- |:-------- |
| 3 to 4 years                | 32%      |
| 4 to 5 years                | 24%      |
| 5 to 6 years                | 16%      |
| 6 to 7 years                | 8%       |
| 7 or more                   | 0%       |

### 4. Effect on LCTs

If transferor dies within 7 years of making an LCT, more IHT may be payable, because:

1. Full death rate of IHT now payable
2. PETs made before the LCT may have become chargeable.

A rate of $\min \left(\text{rate at death}, \text{rate at transfer}\right)$ is used to calculate IHT. Note this means the inheritance tax rate which happens to be in force at the time of death/ transfer. So for our purposes this will always be 40%.

To determine how much of nil rate band is available, find the cumulative total of:

1. Any other LCTs made in 7 years before LCT
2. Any PETs made during 7 years prior to LCT, which have now become chargeable.

So an LCT within 14 years of death may remain relevant for cumulation purposes.

(TODO: consider adding timeline here)

#### Tapering Relief

If >3 years have passed between transfer and death, tapering relief applies to reduce the recalculated tax. Credit given for IHT paid on LCT at the time, though if the recalculated bill is lower than the original amount paid, no tax is refunded.

## Liability and Burden of Payment

Payment will usually be obtained by people holding property in a representative capacity (PRs and trustees), though those who are beneficially entitled to the property are concurrently liable with such representatives.

### Estate Rate

```ad-defn
The average rate of tax applicable to each item of property in the estate.
```

Tax is divided between the various assets in the estate proportionately, according to their value. So multiply the value of the asset by the estate rate to calculate the tax liability of an asset.

### Liability on Death

#### PRs

PRs are liable for IHT attributable to the non-settled estate: any property which 'was not immediately before the death comprised in a settlement' (s 200 IHTA 1984). Includes:

- Property vesting in PRs
- Property to which the deceased was beneficially entitled immediately before death.

```ad-note
PR liability limited to the value of assets received/ would have received but for their own negligence or default. 
```

Concurrently liable with the PRs is ‘any person in whom property is vested…at any time after  
the death or who at any such time is beneficially entitled to an interest in possession in the  
property’ (IHTA 1984, s 200(1)(c)). But unusual for HMRC to claim tax from the recipient of property.

If a deceased gave away a property during their lifetime but retained a benefit in the property, the donee of the gift is primarily liable to pay tax attributable to the property. If tax remains unpaid 12 months after the end of the month of death, PRs become liable.

#### Trustees

Trustees of settlement liable for IHT attributable to the property.

### Liability on PETs

Transferee primarily liable, but PR becomes liable if tax remains unpaid for 12 months after the end of the month of death. PRs should ideally delay distribution of the estate until IHT on lifetime gifts has been paid.

### Liability on LCTs

Transferor primarily liable, though HMRC may also claim tax from trustees. In practice, trustees often pay.

**If transferor pays, the amount of tax will usually be more than if trustees pay**. This is because IHT is charged on the value transferred, i.e., the loss to the transferor's estate brought about by the gift. This is just maths; no more 'efficient' way of doing things.

### Burden

The transferor can decide where the burden of tax falls.

## Time for Payment

### Death Estates

Basic rule: IHT due 6 months after the end of the month of death. If tax not paid on time, interest runs on amount outstanding.

#### Instalments

Instalment option is available

- 10 yearly instalments, first due 6 months after the end of the month of death.
- Tax apportioned using the estate rate
- Applies to:
	- Land
	- Business or interest in business
	- Shares giving control of company to deceased
	- Unquoted shares where holding is sufficiently large (10% nominal value & >£20,000)
	- HMRC thinks lump payment would cause undue hardship
	- IHT payable amounts to $\geq 20\%$ IHT payable on estate.
- For anything except non-agricultural land, instalments carry interest only on late payments
- For non-agricultural land, interest payable on the amount outstanding.
- All outstanding tax and interest payable upon sale.

### PETs

Due 6 months after the end of the month of death.

### LCTs

| Timing                         | Due                                                                                                                                              |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| At the time of transfer        | Generally due 6 months after the end of the month in which LCT made. But for LCTs made 6th April - 30th September, due 30th April the next year. |
| Following death within 7 years | 6 months after the end of the month of death.                                                                                                    |

# Succession to Property on Death

Many valuable assets pass independently of the terms of the will; and even if there is a will, the court may override its terms under the Inheritance (Provision for Family and Dependants) Act 1975 if it concludes that reasonable financial provision was not made for a close relative or dependant.

## Property

An individual can provide for the disposition of their property on death by leaving a valid will. This includes property held in the sole name of the testator at the time of death and any share of property owned as beneficial tenants in common.

If an individual does not dispose of property by will, it can pass on death according to intestacy rules.

### Property Passing Independently of will/ Intestacy

| Property           | Details                                                                                                                                                                                                                                                                  |
| ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Joint property     | Where property held as joint tenants in equity, the property passes by survivorship.                                                                                                                                                                                     |
| Nominated property | Allows individuals to nominate what is to happen to certain types of funds after the nominator's death. Statutory provisions apply to deposits $\leq £5,000$ in certain savings banks/ societies. Nomination takes precedence over any term of the will to the contrary. |
| Insurance policies | A person can take out a life assurance policy expressed to be for the benefit of specified individuals (effectively a gift on trust). Can express the policy to be in favour of spouse/ children/ expressly write the policy in trust.                                   |
| Pension benefits   | Usually, a lump sum is paid to members of the family/ dependents chosen at the trustees' discretion. Common for employees to be allowed to write a letter to trustees saying who they would like to benefit.                                                             |

## Requirements of a Valid Will

```ad-test
title: Valid will
To create a valid will, a testator must have
1. the necessary capacity and intention, and
2. must observe the formalities for execution of wills laid down in the Wills Act 1837. 
```

### Capacity

Individual must be:

- Aged 18 or over
- Must have requisite mental capacity.
	- ‘soundness of mind, memory and understanding’ ([[Banks v Goodfellow (1870) LR 5 QB 549]])
	- Must understand
		- Nature of their act and its broad effects
		- Extent of their property
		- Moral claims they ought to consider.

#### Proof and Presumptions

The person putting forward a will (e.g.., the sole beneficiary) must prove all necessary elements are present. Generally, mental capacity presumed unless there is any sign of mental confusion.

s 3 Mental Capacity Act (MCA) 2005 introduces a statutory test to determine whether a person has capacity to take a decision. This applies only to decisions taken under the Act by the Court of Protection on behalf of another.

### Intention

The testator must have both general intention (to make a will) and specific intention (to make the particular will now being executed).

#### Proof and Presumptions

The burden of proving the testator's knowledge and approval falls on the person putting forward the will.

- General assumption
	- A testator who has capacity and has then read and executed the will is presumed to have the requisite knowledge and approval.
- Exceptions
	- Testator blind/ illiterate/ not signing personally
		- Necessary to provide evidence
		- Usual to include a statement at the end of the will stating that the will was read to/ by the testator, who seemed to know and approve.
	- Suspicious circumstances
		- e.g., the will is prepared by someone who is a major beneficiary under its terms.

#### Conduct

```ad-conduct
Those regulated by the SRA are required to act with honesty and integrity and in the best interests of clients (Principles 4, 5 and 7). They must not abuse their position by taking unfair advantage of clients, and they must not act if there is a significant risk that the duty to act in the best interests of the client conflicts with their own interests. There is such a risk where someone prepares a will which benefits themselves or someone close to them.

It is therefore sensible for firms to have a policy of refusing to act where a client proposes to make a gift of significant value to a fee earner or member of their family unless the client takes independent legal advice.
```

#### Challenging

Where a testator with capacity appears to have known and approved the contents of the will, any person who wishes to challenge the will (or any part of it) must prove **force, fear, fraud, undue influence or mistake**, to prevent some or all of the will from being admitted to probate.

##### Undue Influence

- It is necessary to *prove* undue influence in relation to a will (no presumptions).
- For a lifetime gift made to a person in a position of trust and confidence, there is a presumption of undue influence to be discharge for the gift to be kept.

For a party to prove it has been the victim of undue influence, needs to show:

1. There is a relationship of trust and confidence, and
2. There is a 'transaction which requires explanation' (suspicious/ suspiciously high value).

##### Mistake

- Any words included without the knowledge and approval of the testator will be omitted from probate.
- If there is misunderstanding as to the legal meaning of words used in a will, mistaken words will not be omitted, but may be interpreted to give effect to the wishes of the testator.

#### Formalities

```ad-statute
title: s 9 Wills Act 1837
Signing and attestation of wills

(1) No will shall be valid unless—

- (a) it is in writing, and signed by the testator, or by some other person in his presence and by his direction; and

- (b) it appears that the testator intended by his signature to give effect to the will; and

- (c) the signature is made or acknowledged by the testator in the presence of two or more witnesses present at the same time; and

- (d) each witness either—
	- (i) attests and signs the will; or
	- (ii) acknowledges his signature,

	in the presence of the testator (but not necessarily in the presence of any other witness),

but no form of attestation shall be necessary.

(2) For the purposes of paragraphs (c) and (d) of subsection (1), in relation to wills made on or after 31 January 2020 and on or before 31 January, “presence” includes presence by means of videoconference or other visual transmission.
```

A will made on actual military service or by a mariner or seaman at sea is valid and may be in any form, including a mere oral statement: Wills Act 1837, s 11.

What is required for 'presence' is a line of sight ([[Casson v Dade (1781) 1 Bro C C 99]]) and a consciousness of what is going on ([[Brown v Skirrow [1903] P 3]]).

#### Remote Witnessing

s 2 allows remote witnessing for a limited period.

Must be:

- Witnessed in real time
- Witness and testator can be at different locations
- Electronic signatures not permitted. Testator must date the signature.
- Will must be taken/ posted to witnesses
- Witnesses must physically sign the will in the virtual presence of the testator.
- Witnesses will date with the date on which they are signing
- Execution process complete once both witnesses have signed.
- If testator dies before all signatures added - tough.

#### Proof and Presumptions

```ad-defn
title: Attestation clause
If the will includes a clause which recites that the s 9 formalities were observed ("attestation clause"), a presumption of due execution is raised. The will is valid unless there is proof that the formalities were not observed.
```

If there is no attestation clause, the district judge will require an affidavit of due execution from a witness/ affidavit of handwriting evidence from the testator/ will refer the case to a judge.

#### Witnesses

No formal requirements relating to the capacity of witnesses, though they must be capable of understanding the significance of witnessing a signature.

If either of the witnesses is a beneficiary under the will or is the spouse or a civil partner of a beneficiary, the will remains valid but the gift to the witness or to the witness’s spouse or civil partner fails (Wills Act 1837, s 15).

A solicitor preparing wills should give clear instructions on how to sign and witness the will. If the will is returned to the solicitor for storage, the solicitor is under a duty to check the signatures to see whether ss 9 and 15 appear to  
have been complied with.

#### Revocation

Testators can revoke a will during their lifetime, provided they have testamentary capacity. 3 methods:

1. By a later will or codicil
	- s 20 Wills Act 1837: a will may be revoked in whole or in part by a later will or codicil.
	- Normally, an express clause revoking previous wills and codicils is also included.
	- Exceptionally, the court may decide that an express revocation clause was conditional upon a previous event.
2. By marriage/ civil partnership
	- If testator marries/ forms a civil partnership after executing a will, the will is automatically revoked (s 18 Wills Act 1837).
	- Does not apply when the testator was expecting to marry/ form a civil partnership and appears not to intend the will to be revoked.
	- Where a civil partnership is converted to a marriage, the conversion will not revoke an existing will of either party nor affect any dispositions in the wills.
	- If a testator makes a will and is later divorced, or if a civil partnership dissolved, the will remains valid but
		- Provisions appointing (former) spouse/ civil partner as executor or trustee take effect as if they died on the date the marriage/ civil partnership is dissolved/ annulled.
		- Any property/ interest in property left to former spouse/ civil partner passes as if they had died on that date.
3. By destruction.
	- A will may be revoked by ‘burning, tearing or otherwise destroying the same by the testator or by some person in his presence and by his direction with the intention of revoking the same’ (Wills Act 1837, s 20).
	- Physical destruction without the intention to revoke is insufficient.
	- Symbolic destruction (e.g., crossing words out, writing “revoked”) does not suffice to revoke the whole will, though if a part of the will is completely destroyed/ rendered unreadable, may revoke that part.
	- Destruction must be in the testator's presence and by their direction.

#### Alterations

Basic rule: alterations invalid unless it can be proved they were made before the will was executed/ unless executed like a will. Initials of testator/ witness in margin next to alteration sufficient.

## Mechanism for Effect

- People dealing with estate must decide the effect of the will in the light of the circumstances at the date of the testator’s death.
- If beneficiaries are referred to by description, they must be identified.
- Executors = appointed to deal with estate by will, administrators = deal with estate if there was no appointment in the will. Personal representatives = both.

### Property Passing

Basic rule:

```ad-statute
title: s 24 Wills Act 1837 - A will shall be construed to speak from the death of the testator.

Every will shall be construed, with reference to the real estate and personal estate comprised in it, to speak and take effect as if it had been executed immediately before the death of the testator, unless a contrary intention shall appear by the will. 
```

#### Ademption

A specific legacy will fail if the testator no longer owns the property at death. Gift said to be 'adeemed'.

If the nature of an asset has changed since the will was made, ask whether the asset has changed in name/form or substance. Change in substance → gift adeemed.

Suppose 'my car' is gifted in the will, but subsequently the testator bought a new car. Then generally the gift is adeemed.

```ad-defn
title: Codicil
A supplement to a will which, to be valid, must be executed in the same way as a will. A testator may wish to add to or change a will in a minor way and so may execute a supplementary codicil.
```

A codicil has the effect of republishing the will as at the date of the codicil. So the property referred to is the property at the date of the codicil (i.e., references to items in the will are references to the items on the date of republication).

### Testator Surviving Beneficiary

A gift in a will lapses if the beneficiary dies before the testator. If a legacy lapses, the property falls into residue, unless the testator has provided for the possibility of lapse by including a substitutional gift.

Where no conditions to the contrary are imposed in the will, a gift vests on the testator’s death. There is a presumption that, as regards people, a will is construed at the date it is made.

#### S 184 LPA 1925

```ad-statute
title: s 184 LPA 1925 - Presumption of survivorship in regard to claims to property.

In all cases where, after the commencement of this Act, two or more persons have died in circumstances rendering it uncertain which of them survived the other or others, such deaths shall (subject to any order of the court), for all purposes affecting the title to property, be presumed to have occurred in order of seniority, and accordingly the younger shall be deemed to have survived the elder. 
```

#### Survivorship Clauses

Commonly, gifts in will are made conditional on the survival of the beneficiaries for a specific period, e.g., 28 days.

#### Lapse of Joint Gifts

- A gift by will to two or more people as joint tenants will not lapse unless all the donees die before the testator.
- A class gift (e.g., "to all my nieces") does not lapse unless all members of the class predecease the testator.

#### S 33 Wills Act 1837

Where a will contains a gift to the testator’s child or remoter descendant and that beneficiary dies before the testator, leaving issue of their own who survive the testator, the gift does not lapse but passes instead to the beneficiary’s issue. Section 33 does not apply if the will shows a contrary intention.

(so if testator's kid dies before testator, gift reverts to grandkids).

### Other Reasons for Failure

#### Divorce/ Dissolution

Wills Act 1837, s 18A: where after the date of the will the testator’s marriage or civil partnership is dissolved or annulled or declared void, ‘any property which, or an interest in which, is devised or bequeathed to the former spouse or civil partner **shall pass as if the former spouse or civil partner had died’** on the date of the dissolution or annulment of the marriage or civil partnership.

#### Beneficiary Witnesses Will

s 15: if the beneficiary, their spouse or civil partner witnesses the will, a gift by will fails.

#### Disclaimer

Beneficiaries need not accept gifts given to them by will. If they disclaim the gift, it then falls into residue. A beneficiary who has received a benefit from a gift is taken to have accepted the gift and may no longer disclaim.

#### Forfeiture

Forfeiture Act 1982: A person is not able to inherit from a person they have been convicted of unlawfully killing (as a matter of public policy). Applies to murder or manslaughter (or death by dangerous driving), but not where the killer was insane. Unlawful killing includes aiding, abetting, counselling or procuring the death of another person.

The court has a discretion as to whether or not to grant relief. There is a 3-month time limit to grant relief (s 3(2) Forfeiture Act 1982), starting at the point of sentence.

#### Estates of Deceased Persons (Forfeiture Rule and Law of Succession) Act 2011

Section 2 inserts a new s 33A into the Wills Act 1837 which provides, subject to contrary intention in the will, that a person who disclaims or forfeits an entitlement under a will is to be treated for the purposes of the Wills Act as having predeceased the testator.

#### Identifying Beneficiaries

References to “children” means only biological children and not step-children, unless there is sufficient evidence to the contrary. Adopted children normally treated as children of the adopted parents.

Persons who have obtained a full gender recognition certificate from the Gender Recognition Panel are legally recognised in the acquired gender.

```ad-statute
title: s 15 Gender Recognition Act 2004 
The fact that a person’s gender has become the acquired gender under the Act does not affect the disposal or devolution of property under a will or other instrument made before 4 April 2005.
```

But it will do if the will is made after that date. s 18 GRA 2004: where the disposition or evolution of any property under a will or other instrument (made on or after the appointed day) is different from what it would be but for the fact that a person’s gender has become the acquired gender under the Act, an application may be made to the High Court where expectations have been defeated.

Trustees and PRs are not liable for failing to check a gender recognition certificate etc., though a wronged party can still follow the property and claim it from other beneficiaries.

## Intestacy Rules

Intestacy rules contained in Administration of Estates Act 1925. Can apply when there is no will (person has died interstate), or only a partial will (partial intestacy). Applies only to property which is capable of being left by will.

### Statutory Trust

The intestacy rules impose a trust over all the property (real and personal) in respect of which a person dies intestate (AEA 1925, s 33). This trust is similar to the usual express trust found in a will and includes a power of sale by the PRs. The remaining balance is the 'residuary estate' to be shared among family (s 46 AEA 1925).

### Spouse/ Civil Partner

A spouse is the person to whom the deceased was married at their death, whether or not they were living together. Civil partners are treated in the same way as spouses. Former spouses excluded.

```ad-defn
title: Issue
Includes all direct descendants, as well as adopted children and remoter descendants. Step children not included. 
```

#### Entitlement

Where the intestate is survived by both spouse or civil partner and issue:

- Spouse/ civil partner receives personal chattels absolutely
	- Tangible moveable property
	- Excludes money, investments and items used mainly for business purposes.
- Spouse/ civil partner receives “statutory legacy” tax-free, and costs + interest from death until payment. This is £270,000.
- Residuary estate divided in half.
	- Half held on trust for spouse/ civil partner absolutely
	- Half held for the issue on the statutory trusts.

The intestate’s spouse or civil partner must survive the intestate for 28 days in order to inherit. The Law Reform (Succession) Act 1995 provides that, where the intestate’s spouse or civil partner dies within 28 days of the intestate, the estate is distributed as if the spouse or civil partner has not survived the intestate.

#### Applying Statutory Trusts

Statutory trusts determine membership of the class of beneficiaries:

- Primary beneficiaries are the children of the intestate who are living at the intestate's death
- Interests of children conditional on reaching 18/ marrying/ forming civil partnership before that age.
- If a child predeceased the intestate, any children of the deceased who are living at the intestate's death take their deceased parent's share equally between them, conditional on reaching 18 or marrying/ civil partnership before that.
- If children or issue survive the intestate but die without attaining a vested interest, their interest normally fails, and the estate is distributed as if they had never existed.
	- Unless they leave issue, in which case, issue may be substituted.

#### Appropriation of Matrimonial Home

- The spouse/ civil partner can require PR's to appropriate the matrimonial home in full or partial satisfaction of any absolute interest in the estate (Intestates’ Estates Act 1952, s 5).
- If the property is worth more than the entitlement, the spouse or civil partner may still require appropriation provided they pay the difference, ‘equality money’, to the estate.
- The election must be made in writing to the PRs within 12 months of the grant of representation.

#### No Issue

Where the intestate leaves a surviving spouse or civil partner but no issue, the whole estate, however large, passes to the spouse or civil partner absolutely. The spouse or civil partner must survive the intestate for 28 days in order to take.

#### Distribution Where No Surviving spouse/ Civil Partner

The residue estate is divided between:

1. issue on the ‘statutory trusts’, but if none,
2. parents, equally if both alive, but if none,
3. brothers and sisters of the whole blood on the ‘statutory trusts’, but if none,
4. brothers and sisters of the half blood on the ‘statutory trusts’, but if none,
5. grandparents, equally if more than one, but if none,
6. uncles and aunts of the whole blood on the ‘statutory trusts’, but if none,
7. uncles and aunts of the half blood on the ‘statutory trusts’, but if none,
8. the Crown, Duchy of Lancaster, or Duke of Cornwall (*bona vacantia*).

Each category except parents and grandparents takes “on the statutory trusts”, meaning the members of the class share the estate equally. Relatives not mentioned in s 46 may inherit on intestacy if their parents died before the intestate.

#### Adopted and Illegitimate Children

Adopted children are treated for intestacy purposes as the children of their adoptive parents and not of their natural parents. The intestacy rules are applied regardless of whether or not a particular individual’s parents were married to each other.

On the intestacy of an individual whose parents were not married to each other, it is presumed that the individual has not been survived by their father or by any person related to them through their father unless the contrary is shown, or the father is named on the birth certificate (Family Law Reform Act 1987, s 18(2)).

Upon adoption, vested interests of a child are preserved, and contingent interests may be preserved.

#### Bona Vacantia

Where an estate passes *bona vacantia*, the Crown, Duchy of Lancaster or Duke of Cornwall has a discretion to provide for dependants of the intestate, or for other persons for whom the intestate might reasonably have been expected to make provision.

## Inheritance (Provision for Family and Dependents) Act 1975

I(PFD)A 1975 allows certain categories of people who may be aggrieved because they have been left out of a will, or are not inheriting on an intestacy, or are dissatisfied with the amount they are inheriting, to apply for a benefit from the estate following the testator’s or intestate’s death.

### Time Limit

An application must be brought within **6 months** of the date of issue of the grant of representation to the deceased’s estate (s 4), though the court has discretion to extend.

### Who Can Claim

s 1(1):

- Spouse or civil partner
- Former spouse/ civil partner who has not remarried
- Child
- Step-child/ child of cohabitee
- Person being maintained
- Person living in the same house as the deceased for the whole 2 years before death.

### Proof

The only ground for a claim is that ‘the disposition of the deceased’s estate effected by his will or the law relating to intestacy, or a combination of his will and that law, is not such as to make reasonable financial provision for the applicant’. Section 1(2) sets out two standards for judging ‘reasonable financial provision’.

| Standard                  | Details                                                                                                      |
| ------------------------- | ------------------------------------------------------------------------------------------------------------ |
| Surviving spouse standard (s 1(2)(a)) | Allows a surviving spouse/ civil partner such financial provision as is reasonable in all the circumstances. |
| Ordinary standard (s 1(2)(b))        | For other categories of applicant, allows ‘such financial provision as it would be reasonable in all the circumstances…for the applicant to receive for his maintenance’                                                                                                               |

So a person able to pay for their own maintenance will not obtain any award.

### Factors

s 3(1) provides guidelines of factors which the court considers:

- Financial resources and needs of the applicant
- Deceased's moral obligations
- Size and nature of estate
- Physical/ mental disabilities
- Conduct of applicant and anything else relevant.

### Orders of the Court

The court has wide powers to make orders against the ‘net estate’ of the deceased. The ‘net estate’ against which an order can be made includes not only property which the deceased has, or could have, disposed of by will or nomination, but also the deceased’s share of joint property passing by survivorship if the court so orders.

Any order taken into account for IHT purposes.

### Protecting PRs

Personal representatives should be advised not to distribute the estate until six months have elapsed from the issue of the grant. Must not distribute once they have notice of a possible claim. If PRs do distribute within the six-month period and an applicant subsequently brings a successful claim, the PRs will be personally liable to satisfy the claim if insufficient assets remain in the estate.

# Probate

## Introduction

It is necessary for assets to be transferred upon death into the names of beneficiaries. Normally necessary to obtain a court document authorising the deceased's PRs to transfer assets. Known as a **grant of representation**.

The process of applying for a grant is governed by the Non-contentious Probate Rules 1987 (NCPR 1987) as amended.

### Digital Probate

Professionals are obliged to apply for grants of probate online, subject to certain exceptions.

Where applications are made online, supporting documentation, such as the death certificate, original will and HMRC forms have to be sent separately to HMCTS Probate at Harlow where they are scanned.

### Fees

The application fee is £273 where the estate exceeds £5,000. There is no fee if the estate is £5,000 or less.

## PRs

- If the will is valid and contains an effective appointment of executors of whom one or more is willing and able to prove the deceased’s will, a grant of probate will be issued to the executor(s) willing to act.
- If there is a valid will, but there are no persons willing or able to act as executors, then the next persons entitled to act are administrators with the will annexed.
- If a deceased left no will, or no valid will, the estate will be administered in accordance with the law of intestacy by administrators appointed by the application of NCPR 1987, r 22.

| PR            | Number of PRs required                                                                                                                                                                                                                                      | Authority                                                                                                                            |
| ------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| Executor      | One executor may obtain a grant and act alone, even if the estate contains land which may be sold during the administration. Note the difference with a trust, where two trustees are needed.                                                               | An executor derives authority to act in the administration of an estate from the will. The grant of probate confirms that authority. |
| Administrator | In the case of administrators (with or without the will), it is normally sufficient for one to act in the administration of the estate. However, where the will or intestacy creates a life or minority interest, two administrators are normally required. | An administrator (with or without the will) has very limited powers before a grant is made. Their authority stems from the grant which is not retrospective to the date of death.                                                                                                                                     |

### First Steps

| Step                   | Details                                                                                                                                                                 |
| ---------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Will                   | If there is a will, ensure all executors named receive copies.                                                                                                          |
| Funeral directions     | Check any special directions as to cremation/ use of body for medical research, etc.                                                                                    |
| Assets and liabilities | Obtain details of the deceased’s property and of any debts outstanding at the date of death.                                                                            |
| Beneficiaries          | Identify beneficiaries and entitlements, whether gifts are part of estate, and whether beneficiaries are alive. Inform beneficiaries that personal data is held (GDPR). |

### Missing/ Unknown Creditors and Beneficiaries

PRs are responsible for administering the estate correctly. If the PRs fail to pay someone who is entitled either as a creditor or as a beneficiary, they will be personally liable to that person.

PRs can protect themselves against unknown claims by advertising for claimants complying with the requirements of the Trustee Act 1925, s 27. Provided they wait for the time period specified in the section (at least two months), the PRs will be protected from liability if an unknown claimant later appears. However, the claimant will have the right to claim back assets from the beneficiaries who received them.

#### Advertising

- Advertise as early as possible
- Can use the following methods:
	- Advertisement in the London Gazette
	- Advertisement in a local newspaper of the area
	- Such other like notices.
- Include time limit in notice for persons to come forward, which must be not less than 2 months from date of notice.
- Make searches in the case of land, to check any benefits or burdens.

After notice has expired, PRs should distribute the estate.

#### Liability

Trustee Act 1925, s 27 exempts trustees from liability from unknown claims provided they have advertised as above. But does not protect PRs who knows there is a person with a claim but cannot find them.

#### Missing Known creditors/ Beneficiaries

Options:

1. Retain some assets in case claimant appears
2. Take an indemnity from beneficiaries that they will meet any claims if claimant reappears (dangerous for the PR)
3. Take out insurance to provide funds. Can be expensive
4. Apply to court for a *Benjamin* order: an order for distribution on the basis that the claimant is dead. Protects PR from liability, though claimant retains the right to recover assets from beneficiaries.

## Necessity of Grant of Representation

Not always necessary to obtain a grant of representation.

### Assets Passing to PRs without a Grant

- Orders made under Administration of Estates (Small Payments) Act 1965 permits payments $\leq £5,000$ to persons appearing to be beneficially entitled to the assets without formal proof of title.
- Chattels
- Cash

### Assets Not Passing Through PR

- Beneficially joint property passes by survivorship to the surviving joint tenant.
- But transferring tenants in common property requires a grant of representation.

### Property Not Forming Part of Estate

- A life insurance policy held on trust for another. The proceeds make tax-free provision for dependents of the deceased.
- Death in service benefits under a pension scheme. Tax-free provision for dependants.

## Applying for Grant

A grant of representation is an order of the [[High Court]].

Documents to submit:

- HMRC Form IHT421 (confirming payment of IHT) or Form IHT205 if the estate was 'excepted'.
- Deceased's will and codicil, plus 2 photocopies.
- Any supporting evidence required
- Probate court fees (£173 if estate $\geq £5,000$).
- Form PA1P/ PA1A (will/ no will) if paper application.

### Admissibility of Will

To ensure the will is admissible, check:

- The will is the last will
- Will has not been validly revoked
- Executed in accordance with s 9 Wills Act 1837
- Contains an attestation clause raising a presumption of due execution.

### Additional Requirements

Registrar may require further evidence, in the form of a statement of truth/ affidavit. This may include:

- Evidence of due execution and/or capacity
	- If there is no attestation clause/ other defect, some sort of attesting witness statement will be required.
	- If mental capacity is doubted, a witness statement from a doctor may be necessary.
- Evidence as to knowledge and approval
	- Registrar may doubt whether the testator was aware of the contents of the will on execution.
	- Affidavit/ witness statement will be requested.
- Evidence as to remote witnessing
- Evidence as to plight and condition.
	- If the state of the will suggests it has been interfered with since execution, further evidence will be required.

A will known to have been in the testator's possession but which cannot be found following death will be presumed to have been destroyed by the testator with the intention of revocation. If the will is lost/ destroyed accidentally, a copy/ reconstruction can be used, together with suitable witness affidavits and witness statements.

## Completing IHT Account

- If the estate is not an excepted estate, PRs will prepare an IHT400.
- The IHT400 is an inventory of the assets to which the deceased was beneficially entitled and of their liabilities, and is the form for claiming reliefs and exemptions and calculating the IHT payable.
- It should be delivered within 12 months of the end of the month in which the death occurred.
- Where IHT is payable, it is necessary to apply for a reference number before submitting the IHT400 (schedule IHT422).
- To claim the unused nil rate band of a spouse, PRs of the survivor must make a claim using schedule 402.  
- To claim the unused RNRB of a spouse, PRs of the survivor must make a claim using schedule 436.

### Paying IHT

- IHT on property without the right to pay by instalments must be paid within 6 months of the end of the month in which the death occurred. Failure to do so causes interest to become payable.
- Where property qualifies for the right to pay by instalments, no tax is due until the expiry of the first 6-month period. Interest runs on all tax not paid at the due date.
- Tax payable on the estate is apportioned between the instalment and non-instalment option property.

### Valuations

Assets in the estate are valued at ‘the price which the property might reasonably be expected to fetch if sold in the open market’ immediately before the death (IHTA 1984, s 160).

#### Jointly-owned Assets

Where the deceased was a co-owner of the land at their death, the market value of the land will normally be discounted by 15% (residential property) or 10% (investment property), to reflect the difficulty of selling a part interest in land.

The discount is not available for co-ownership of assets other than land. Where the co-owners of land are spouses/ civil partners, generally no discount in value is allowed.

### Funding IHT

Where there is tax to pay on delivery of an IHT400, the PRs must arrange for the money to be sent to HMRC. HMRC sends the probate summary (IHT421) to the Probate Service, so grant can be issued. Funding the tax bill may be difficult, since the deceased's assets vesting in PRs are 'frozen' until the grant issues. There are some options.

- Direct payment scheme
	- There is a procedure allowing PRs to arrange payment of IHT to HMRC directly from the deceased's accounts. The scheme is voluntary on the part of institutions.
	- Procedure:
		1. PRs provide identification to bank
		2. PRs complete and send IHT423 form to bank, as well as sending IHT400 and supporting schedules to HMRC.
		3. Bank sends money direct to HMRC.
		4. HMRC sends receipted Probate Summary (IHT421) to Probate Service.
	- This process is usually slow. Solicitors can make private arrangements with the bank, for the transfer of funds from the deceased's account.
- Life assurance
	- A life assurance company may be willing to release funds to pay IHT directly to HMRC.
- Assets realisable without grant
	- See Administration of Estates (Small Payments) Act 1965.
- Loans from beneficiaries
	- Wealthy beneficiaries may be prepared to fund the tax from their own resources, on condition that they will be repaid from the deceased’s estate once the grant issues.
- National savings and government stock
	- Payment of tax may also be made from National Savings Bank accounts or from the proceeds of National Savings Certificates/ investments.
- Bank borrowing
	- Banks will often lend against an undertaking to repay the loan given by the PRs, along with (often) an undertaking from the solicitor to repay the loan from the proceeds of the estate.
- Heritage property
	- Taxpayers can offer HMRC an asset in lieu of tax (IHTA 1984, s 230(1)). The Secretary of State must agree to accept such assets and the standard required of such objects is very high.
- Obtaining a grant on credit
	- The grant of probate can be obtained on credit in exceptional circumstances where PRs can demonstrate that it is impossible to pay IHT in advance.

```ad-conduct
An undertaking should be limiited to "such proceeds as come into the solicitor's control".
```

## Excepted Estates

### Inheritance Tax (Delivery of Accounts) (Excepted Estates) Regulations 2004

If the estate is excepted, PRs do not now submit any IHT form to HMRC. Instead, information as to value of the estate is included on the forms submitted to the Probate Service which the Probate Service must pass on to HMRC within one month.

HMRC has **60 days** from the issue of the grant of representation to ask for additional information. If no such request is made, the estate receives **automatic clearance**.

The requirements for qualifying as an excepted estate have been relaxed in response to the criticisms of the Office of Tax Simplification, allowing many more estates to qualify.

There are 3 categories of excepted estates.

| Category                             | Details                                                                                                                                                                                                                                                                               |
| ------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Category 1 - small estates           | Estates where the gross value on death for IHT purposes + chargeable value of any specified transfers does not exceed nil rate threshold. Nil rate threshold is increased to take account of any transferred nil rate band.                                                           |
| Category 2 - 'exempt' estates        | Estates where the bulk of the estate attracts the spouse/ civil partner or charity exemption. The gross value of the estate + specified transfers must not exceed £3 million. Net chargeable estate after deduction of liabilities and exemptions must not exceed nil rate threshold. |
| Category 3 - 'non-domiciled' estates | Where the deceased was never domiciled or treated as domiciled in the UK, and owned only limited assets in the UK.                                                                                                                                                                                                                                                                                      |

```ad-defn
title: Specified transfers
Chargeable transfers of cash, personal chattels, tangible moveable property, quoted shares, or an interest in land, made in the 7 years before death. When valuing specified transfers, business and agricultural property relief is ignored. 
```

```ad-defn
title: Specified exempt transfers
Transfers of value made in 7 years before death which fall under one of the exceptions:
- s 18 (transfers between spouses (or civil partners));
- s 23 (gifts to charities);
- s 24 (gifts to political parties);
- s 24A (gifts to housing associations);
- s 27 (maintenance funds for historic buildings, etc); or
- s 28 (employee trusts).
```

### Procedure

On the application of grant, PRs provide details of the deceased, the value of their estate and details of any nil rate band.

```ad-defn
title: Estate
For this purpose, estate means the total of the death estate + specified transfers + specified exempt transfers made $\leq 7$ years before death.
```

HMRC will select a random sample to review within 60 days of the application for grant.

## IHT400

Must be used whenever the deceased dies domiciled in the UK and the estate is not an excepted estate. PRs must complete Form IHT400 and relevant supporting schedules and sign a declaration of truth. Schedules required will vary according to the composition of the estate.

IHT400 required $\implies$ IHT421 (Probate Summary) must be completed and submitted alongside. Sets out the gross and net values of the estate for probation purposes.

- Probate value is not reduced by IHT exemptions and reliefs.
- Probate value does not include the value of the property passing by survivorship or under the terms of a trust.

HMRC will, if satisfied, receipt the IHT421 and forward it to the Probation Service. This is proof that the relevant IHT has been paid. HMRC recommends allowing 20 working days between sending the IHT400 and applying for grant.

## PA1P And PA1A

Applications for a grant of representation can be verified against a statement of truth and without the will having to be marked with the signature of the applicant.

| Is there a will? | Form to use |
| ---------------- | ----------- |
| Yes              | PA1P        |
| No               | PA1A            |

Online applications are made using one form, with different sections for the different options.

### Purpose of Application Forms

1. Establish basis of the applicants' claim to be entitled to take the grant
2. Confirm that PRs will carry out their statutory duties
3. Identify the will and any codicils to it.

### Points in Common

Both forms have sections for:

- Identifying the applicants
	- Name
	- Address
	- Identification documents
- Identifying the deceased
	- Name
	- Marital status at death
	- Total of foreign assets
	- Any legally adopted/ adopted out relatives.
- Applications as attorney
	- Common for persons to apply for a grant as an attorney on behalf of the person entitled to take out the grant.
	- Where no attorney has been appointed, a grant will be made to another person for use and benefit of the incapacitated person.
- Foreign domicile
	- To obtain a grant for a person domiciled abroad, extra information about the entitlement to take out a grant is needed.
- IHT estate and probate estate
	- Applicant must state whether an IHT400 or IHT421 was completed.
	- Provide details on excepted estate if relevant.
- Legal statements
	- Applicants confirm that the will & codicils is last will and testament of the person who died.
	- Applicants will collect the whole estate
	- Applicant will provide full details of the estate and how it has been distributed.
	- Applicant understands that application will be rejected if information not provided.
	- Applicant understands that proceedings for contempt of court will be brought if there is evidence of dishonesty.

## PA1P

Completed whenever there is a will, and irrespective of whether the grant sought is a grant of probate or a grant of letters of administration with the will.

- Identification of will
	- Original will, and any codicils must accompany the application must be provided.
	- Must include date of will, and details of any foreign wills.
	- Question of whether there are any minor beneficiaries (in which case two administrators must be appointed, if the application is by non-executors).

### Executors

- Entitlement of executors to act
	- Executors have the best right to take a grant of probate. One executor may obtain a grant and act alone.
- Executor lacking capacity
	- Capacity to act as executor is judged at the time of the application for the grant. A person appointed as an executor who lacks capacity to make decisions cannot apply for the grant.
	- In the case where all executors lack capacity, the court can intervene/ give executor power to the attorney/ give executor power to the person entitled to the residuary estate.
- Minors
	- An executor who is a minor at the testator's death cannot act as executor/ obtain a grant of probate.
	- If only a minor is appointed, a grant of letters of administration with will annexed for the use and benefit of the minor can be made (?)
- Spouse/ civil partner
	- If spouse appointed and marriage/ civil partnership fails, appointment will fail unless the testator has shown a contrary intention in the will.
- Renunciation
	- Persons appointed as executors may renounce their right to take the grant, provided that they have not 'intermeddled' (e.g., notifying the deceased's bank of the death).
	- Renunciation must be made using Form PA15, signed by the renouncer and filed with the Probate Service.
	- Executors also appointed trustees will remain trustees despite renouncing executorship.
- Power reserved
	- No limit on how many executors can be appointed
	- Probate will be granted to a maximum of 4 executors in respect of the same property.
	- No need for every executor to act.
	- Possible to obtain a grant limited to only part of the estate.

### Administrators

- Entitlement of administrators to act.
	- If there is a valid will but no executor able or willing to act, the appropriate grant is still letters of administration with will annexed.
	- The order of priority of person(s) entitled to a grant of letters of administration with will annexed is governed by **NCPR 1987, r 20**:
		1. Executor
		2. Anyone entitle to residue also holding it in trust for another
		3. Any other residuary legatee
		4. PR of any of the above
	- If there is more than one person of equal rank and they both apply separately, the court will prefer an application from a beneficiary with a vested, as opposed a contingent interest.
- Clearing off
	- A person in a lower-ranked category may apply only if there is nobody in a higher category willing and able to take the grant.
- Minors
	- A minor cannot act as administrator with will annexed, nor can they apply for grant.
	- Parent/ guardian may apply for a grant "for the minor's use and benefit".
- Number of administrators
	- Maximum of 4 in relation to the same property (s 114 SCA 1981).
	- If there are multiple people entitled to act as administrator, a grant can be made on the application of any one of them without notice to the other(s) (r 27(4) NCPR 1987).
- Need for 2 administrators
	- If there is a life interest or property passing to a minor, the court normally requires a minimum of 2 administrators to apply for the grant (s 114 SCA 1981).
	- But the court has discretion to only require 1
- Renunciation
	- Any person entitled to apply for a grant of letters of administration with will annexed can renounce in the same way as an executor (though using a Form PA16), except that an administrator does not lose the right to renounce by intermeddling.

## PA1P

Completed where the deceased died without a valid will.

```ad-statute
title: r 22 NCPR 1987
(1) Where the deceased died on or after 1 January 1926, wholly intestate, the person or persons having a beneficial interest in the estate shall be entitled to a grant of administration in the following classes in order of priority, namely—
- (a) the surviving husband or wife;
- (b) the children of the deceased and the issue of any deceased child who died before the deceased;
- (c) the father and mother of the deceased;
- (d) brothers and sisters of the whole blood and the issue of any deceased brother or sister of the whole blood who died before the deceased;
- (e) brothers and sisters of the half blood and the issue of any deceased brother or sister of the half blood who died before the deceased;
- (f) grandparents;
- (g) uncles and aunts of the whole blood and the issue of any deceased uncle or aunt of the whole blood who died before the deceased;
- (h) uncles and aunts of the half blood and the issue of any deceased uncle or aunt of the half blood who died before the deceased.
```

### Clearing Off

An applicant under r 22 must make clear that there is no one in a higher category able to apply for the grant (again, this is called ‘clearing off’) and describe their own relationship to the deceased.

### Beneficial Interest

Unless the application is made by the Treasury Solicitor or a creditor, the applicant must have a beneficial interest in the estate (or would have such an in interest if there was an accretion to the estate) by virtue of the intestacy rules.

### Minors

A minor cannot act as administrator and cannot apply for grant.

### Renunciation

A person entitled to a grant under NCPR 1987, r 22 can renounce their right to the grant in the same way as an administrator with the will annexed. If they are the only relative of the deceased with a beneficial entitlement, the grant will be made to a creditor of the deceased.

Common for a creditor to take the grant if the estate is insolvent.

### Number of Administrators

- The grant will issue to a maximum of four administrators. If there are more than four people with an equal entitlement, it is not possible to have ‘power reserved’ to a non-proving administrator.
- Where two or more people are entitled in the same degree, a grant can be made on the application of any one of them without notice to the other(s).
- A minimum of two administrators is generally required where the intestacy creates minority interests through property being held for minors on the ‘statutory trusts’.

## Effect of Grant

| Type of grant                                  | Effect                                                                                                                        |
| ---------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| Grant of [[Probate]]                           | Confirms the authority of the executors which stems from the will and arises from the time of death of the testator's estate. |
| Grant of administration (with or without will) | Confers authority on the administrator and vests the deceased's property in the administrator. Until grant issued, the administrator has no authority and property is vested in the President of the Family Division.                                                                                                                               |

## Limited Grant

A grant of representation is normally general. Can be limited:

- To a specific part of a deceased's property
- To settled land
- To a special purpose (e.g., for a minor's use and benefits).

## Death of PR

If there are several proving PRs administering an estate and one dies after taking the grant but before the administration has been completed, the surviving PRs continue to act. Where the death leaves a sole surviving PR, the court may exercise its powers to appoint an additional PR.

If a person entitled to be the PR (either as the executor under a will, or by virtue of NCPR 1987, r 20 or r 22) survives the deceased but then dies themselves without taking out a grant of representation, the AEA 1925, s 5 provides that their rights concerning the grant die with them.

### Chain of Representation

The office of executor is personal to the executor appointed by the testator in their will.  
Because it is an office of personal trust an executor cannot assign that office (although they can appoint an attorney).

```ad-statute
title: s 7 AEA 1925
(1) An executor of a sole or last surviving executor of a testator is the executor of that testator.

This provision shall not apply to an executor who does not prove the will of his testator, and, in the case of an executor who on his death leaves surviving him some other executor of his testator who afterwards proves the will of that testator, it shall cease to apply on such probate being granted.

(2) So long as the chain of such representation is unbroken, the last executor in the chain is the executor of every preceding testator.

(3) The chain of such representation is broken by—
- (a) an intestacy; or
- (b) the failure of a testator to appoint an executor; or
- (c) the failure to obtain probate of a will;

but is not broken by a temporary grant of administration if probate is subsequently granted.

(4) Every person in the chain of representation to a testator—
- (a) has the same rights in respect of the real and personal estate of that testator as the original executor would have had if living; and
- (b) is, to the extent to which the estate whether real or personal of that testator has come to his hands, answerable as if he were an original executor.
```

### Grant *de Bonis Non administratis*

In situations where the chain of representation does not apply because there are no successive proving executors, a *grant de bonis non administratis* must be obtained to the original estate.

It is issued in estates where the sole, or sole surviving, PR has died after obtaining the grant but without having completed the administration, and it relates only to the un-administered part of the estate.

Two requirements apply:

1. there must have been a prior grant of probate or letters of administration to a PR who has now died; and
2. the chain of representation must not apply.

## Caveats and Citations

Available to assist in a dispute over the right to take out a grant of representation to an estate.

### Caveats (NCPR 1987, R 44)

The effect of a caveat is to prevent the issue of a grant of representation. The person lodging or entering a caveat is called a ‘caveator’. A caveat might be used, for example, where a beneficiary believes the executor named in the will lacks the mental capacity to act, or where the validity of the will is questioned.

An application for a caveat can be made online or using paper form PA8A.

### Citations (NCPR 1987, R 46)

If the person initially entitled to take the grant refuses to do so and also refuses to renounce, the estate would remain un-administered and the beneficiaries would be left waiting indefinitely for their inheritance. In such circumstances, a citation provides a remedy.

| Type of citation                    | Details                                                                                                                                                                           |
| ----------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Citation to take probate            | May be used where an executor has lost their right to renounce probate by intermeddling in the estate, but has not applied for a grant of probate and shows no signs of doing so. Once cited, the executor must proceed with an application for the grant of probate. If they do not, the citor can apply to the court for an order allowing the executor to be passed over. |
| Citation to accept or refuse a gift | Standard method of clearing off a person with a prior right to any type of grant who has not applied, and shows no intention of applying, for a grant.                                                                                                                                                                                  |

## Alternative

If a person is unwilling to act as executor in the administration of an estate, it is often preferable to apply to the Probate Service under the Senior Courts Act 1981, s 116 for an order passing over that person in favour of someone else.

# Administration of Estate

## Introduction

After PRs have obtained the grant, they must administer the estate. Includes:

- Collecting deceased's assets
- Paying funeral and testamentary expenses and debts
- Distribute the legacies
- Complete administration and distribute residual estate.

## Administration Period

MERMAID1

But PR holds office for life, so must deal with further assets and liabilities if they are later discovered.

## PR Duties

```ad-statute
title: s 25, Administration of Estates Act 1925
The personal representative of a deceased person shall be under a duty to collect and get in the real and personal estate of the deceased and administer it according to law.
```

PR **personally liable** for losses to the estate resulting from any breach of duty they commit.

```ad-statute
title: s 61 Trustee Act 1925 - Power to relieve trustee from personal liability.
If it appears to the court that a trustee, whether appointed by the court or otherwise, is or may be personally liable for any breach of trust, whether the transaction alleged to be a breach of trust occurred before or after the commencement of this Act, but has acted honestly and reasonably, and ought fairly to be excused for the breach of trust and for omitting to obtain the directions of the court in the matter in which he committed such breach, then the court may relieve him either wholly or partly from personal liability for the same. 
```

There may be a clause in the will providing protection from liability for mistakes made in good faith.

## Protection Against Liability

- s 27 TA 1925 protects against personal liability to unknown beneficiaries when requirements are complied with.
- But does not protect against claim from missing known beneficiaries:
	- Use a Benjamin order. The court will require evidence that full enquiries were made to find the missing person.
	- Or take out insurance (may be cheaper).
- Inheritance (Provision for Family and Dependants) Act 1975
	- PRs will be personally liable if a successful application for “reasonable financial provision” is made.
	- Protect against liability by waiting **$>6$ months from the date of grant of representation** before distributing assets/ retaining sufficient assets to deal with any such claim after 6 months.

## Administrative Powers

TA 2000 prescribes powers to invest trust property, appoint agents of agents and nominees, remuneration of trustees and to insure trust property. A duty of care is imposed, having regard to special knowledge/ skills of the trustee.

### Powers Granted by Will

- Many statutory powers can be varied by express provision in the will.
- Will can grant additional powers.
- Will drafting
	- Good practice to fully set out the powers of the executors
	- $\exists$ STEP (Society of Trust and Estates Practitioners) Standard Provisions

#### Administration of Estate Provisions

| Topic                                                        | Statutory provisions                                                                                                                                                                                                                                                                        | Possible will provision                                                                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| Power to appropriate assets without consent of beneficiaries | s 41 AEA 1925: PRs have power to appropriate any part of the estate in/ towards satisfaction of a legacy/ share of residential estate, provided the appropriation does not prejudice any specific beneficiary. Beneficiary must consent to the appropriation.                               | Relieve trustees of the duty to ask consents of beneficiaries. A general power to re-appropriate assets for trustees is useful. |
| Power to insure                                              | s 19 TA 1925: PRs and trustees have power to insure trust property against any risks, to the full value of the property, and to pay premiums out of capital or income.                                                                                                                      | Can give trustees the power to insure the life of the beneficiary/ settlor.                                                     |
| Power to accept receipts from/ on behalf of minors           | Generally, unmarried minor cannot ive a good receipt for capital or income. Married minor can give good receipt for income (s 21 LPA 1925). s 3 Children Act 1989 provides that parents with parental responsibility have the right to receive/ recover money for the benefit of the child. | Allow PRs to accept receipt from a child over 16/ leave legacy to trustees for the benefit of a minor.                          |

#### Administration of Trusts Provisions

In many cases, PRs will hold the residue of the estate as trustees:

1. Where the beneficiary has a contingent interest
2. Where the interests in the property are divided (e.g., between income and capital).

| Topic                                              | Statutory provisions                                                                                                                                                                                                                                                                                                                   | Possible will provision                                                                                                                                                                                           |
| -------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Power to invest trust funds                        | s 3 TA 2000: general power of investment (though excludes investments in land, other than by mortgage) Trustees required to take proper advice and review investments periodically. Must have regard to standard investment criteria.                                                                                                  | Express clause not necessary                                                                                                                                                                                      |
| Power to purchase land                             | s 8 TA 2000:: trustees have the power to acquire freehold or leasehold land in the UK. Does not allow foreign purchases of land/ purchasing interest in land with someone else.                                                                                                                                                        | Express clause to widen powers                                                                                                                                                                                    |
| Power to sell personalty                           | There is doubt over whether trustees who do not hold land have an implied power of sale                                                                                                                                                                                                                                                | Many wills continue to impose an express trust for sale over residue.                                                                                                                                             |
| Power of maintenance                               | s 31 TA: power to use income for minor's maintenance, education or benefit. Income paid to beneficiary once they reach 18.                                                                                                                                                                                                             | Can change the relevant age from 18 to 21.                                                                                                                                                                        |
| Power to apply capital                             | s 32 TA 1925: allows trustees to permit a beneficiary with an interest in capital to have the capital applied for their benefit before they are entitled to receive it. The amount applied can be up to the level of the beneficiary's vested share. Advance made must be brought into account on the final distribution (s 32(1)(b)). | Can give trustees discretion over how to bring into account any payments received by beneficiaries. Can give trustees the power to give or lend capital from the fund to someone with an interest only in income. |
| Power to accept receipts from/ on behalf of minors | Statutory powers of maintenance and advancement as above.                                                                                                                                                                                                                                                                              | Not needed                                                                                                                                                                                                        |
| Control of trustees by beneficiaries               | s 19 TLATA 1996 provides that beneficiaries of full age and capacity together entitled to the whole fund may direct trustees to retire and appoint new trustees.                                                                                                                                                                       | s 19 TLATA can be excluded.                                                                                                                                                                                       |
| Trusts of land: duty to consult beneficiaries      | s 11 TLATA: trustees dealing with land must consult any beneficiary who is of full age and beneficially entitled to an interest in possession in the land. Must give effect to the wishes of such a beneficiary, so far as is consistent with the general interest of the trust.                                                       | Often excluded in the will.                                                                                                                                                                                       |
| Trusts of land: beneficiary's rights of occupation | s 12: Beneficiary with a beneficial interest in possession has the right to occupy land in some circumstances                                                                                                                                                                                                                          | No power to exclude, but can make a declaration that the purpose of the trust is not for the occupation of land.                                                                                                  |
| Balance between beneficiaries                      | Trustees are under a duty to ensure a fair balance between the interests of beneficiaries.                                                                                                                                                                                                                                             | Authorise trustees to treat the interests of one beneficiary as of paramount importance.                                                                                                                          |

### Maintenance and Advancement

When considering their dispositive powers and obligations it is important for trustees to distinguish between the trust capital and the income generated by that capital.

- In some cases different beneficiaries will be entitled to the income and the capital. A good example is a life interest trust.
- In other cases, the same beneficiary may be entitled to both capital and income but not necessarily at the same time:
	- A beneficiary may have a right to receive capital upon the occurrence of a particular event, such as reaching a specified age. In the meantime, they may be entitled to receive the income as it arises.
	- Alternatively, the trustees may have a power or obligation to accumulate the income (i.e. add it to the capital). If the income is accumulated, the beneficiary will not receive anything until it is time for the capital to be distributed.

Can a beneficiary ever make an early claim to the capital or accumulated income?

#### Entitlement to Income

Adult beneficiaries with vested interests in trust property will usually have a right to receive the trust income as it arises.

Adult beneficiaries with contingent interests have a statutory right under [s 31(3) Trustee Act 1925](https://www.legislation.gov.uk/ukpga/Geo5/15-16/19/section/31) (‘TA 1925’) to receive income if the trust ‘carries the intermediate income’ (i.e., the income produced between creation of the contingent interest and satisfaction of the contingency). The circumstances in which a trust ‘carries the intermediate income’ are beyond the scope of this module. If it is relevant to the analysis, a question will specify whether a contingent interest carries the intermediate income.

Minor beneficiaries will not usually be entitled to receive trust income until they reach the age of 18.

However, s 31(1) TA 1925 gives the trustees a **power of maintenance**. This allows the trustees to pay trust income to beneficiaries who would benefit from receiving it immediately, instead of waiting for their interest to vest in possession.

Note that the provisions of s 31 TA 1925 may be excluded or varied by a trust instrument: [s 69(2) TA 1925](https://www.legislation.gov.uk/ukpga/Geo5/15-16/19/section/69).

#### Power of Maintenance

```ad-statute
title: s 31 TA 1925 -  Power to apply income for maintenance and to accumulate surplus income during a minority.

(1) Where any property is held by trustees in trust for any person for any interest whatsoever, whether vested or contingent, then, subject to any prior interests or charges affecting that property—
- (i) during the infancy of any such person, if his interest so long continues, the trustees may, at their sole discretion, pay to his parent or guardian, if any, or otherwise apply for or towards his maintenance, education, or benefit, the whole or such part, if any, of the income of that property as the trustees may think fit, whether or not there is—
	- (a) any other fund applicable to the same purpose; or
	- (b) any person bound by law to provide for his maintenance or education; and
- (ii) if such person on attaining the age of eighteen years has not a vested interest in such income, the trustees shall thenceforth pay the income of that property and of any accretion thereto under subsection (2) of this section to him, until he either attains a vested interest therein or dies, or until failure of his interest:

(2) During the infancy of any such person, if his interest so long continues, the trustees shall accumulate all the residue of that income by investing it, and any profits from so investing it from time to time in authorised investments, and shall hold those accumulations as follows:—
- (i) If any such person—
	- (a) attains the age of eighteen years, or marries under that age or forms a civil partnership under that age, and his interest in such income during his infancy, or until his marriage or his formation of a civil partnership, is a vested interest or;
	- (b) on attaining the age of eighteen years or on marriage, or formation of a civil partnership, under that age becomes entitled to the property from which such income arose in fee simple, absolute or determinable, or absolutely, or for an entailed interest;
- the trustees shall hold the accumulations in trust for such person absolutely, but without prejudice to any provision with respect thereto contained in any settlement by him made under any statutory powers during his infancy, and so that the receipt of such person after marriage or formation of a civil partnership, and though still an infant shall be a good discharge, and
- (ii) In any other case the trustees shall, notwithstanding that such person had a vested interest in such income, hold the accumulations as an accretion to the capital of the property from which such accumulations arose, and as one fund with such capital for all purposes, and so that, if such property is settled land, such accumulations shall be held upon the same trusts as if the same were capital money arising therefrom;

but the trustees may, at any time during the infancy of such person if his interest so long continues, apply those accumulations, or any part thereof, as if they were income arising in the then current year.

(3) This section applies in the case of a contingent interest only if the limitation or trust carries the intermediate income of the property, but it applies to a future or contingent legacy by the parent of, or a person standing in loco parentis to, the legatee, if and for such period as, under the general law, the legacy carries interest for the maintenance of the legatee, and in any such case as last aforesaid the rate of interest shall (if the income available is sufficient, and subject to any rules of court to the contrary) be five pounds per centum per annum.

(4) This section applies to a vested annuity in like manner as if the annuity were the income of property held by trustees in trust to pay the income thereof to the annuitant for the same period for which the annuity is payable, save that in any case accumulations made during the infancy of the annuitant shall be held in trust for the annuitant or his personal representatives absolutely.

(5) This section does not apply where the instrument, if any, under which the interest arises came into operation before the commencement of this Act.
```

Where a minor has a vested interest in trust property (or a contingent interest which carries the intermediate income), the trustees have a wide statutory power under [s 31 TA 1925](https://www.legislation.gov.uk/ukpga/Geo5/15-16/19/section/31) to pay the income as they think fit. The trustees may:

- Pay the income to the child or their parent or guardian.
- Apply the income directly for the child’s ‘maintenance, education or benefit’.

This power may be used even if there is another fund available for the same purpose or other persons legally obliged to provide for the child.

Income which is not paid out under s 31 must be accumulated but can still be paid out subsequently using the power of maintenance as long as the beneficiary remains under 18.

Once the beneficiary reaches 18, the accumulated income is added to the capital and can no longer be accessed by the beneficiary until they are entitled to receive the capital.

Income generated after the beneficiary is 18 must be paid directly to them. Although the power of maintenance gives the trustees a broad discretion, the following points must be noted:

1. The power of maintenance is a **fiduciary power**. The trustees must consciously consider the exercise of the power and, if they choose to exercise it, must act in good faith in the interests of the beneficiary.
2. The income must be used for the primary benefit of the minor beneficiary, but it does not matter that it may therefore indirectly benefit their parent or guardian.
3. It is an improper exercise of the power to unquestioningly pay it to the minor’s parent or guardian See e.g. [[Wilson v Turner (1883) 22 Ch. D. 521]]

Because the power of maintenance only applies during the minority of a beneficiary, it is good practice for trustees to consider exercising the power shortly before the beneficiary turns 18, particularly if the beneficiary has a contingent interest to the trust capital.

If it is not exercised at this time, all accumulated income will become part of the trust capital and the beneficiary will not be able to access it until their interest in the capital vests.

```ad-example
A testator leaves an estate on trust for A (26), B (19) and C (16) in equal shares upon their reaching 25.

A has reached the age of 25 so their share has vested in possession and should be distributed.

B’s share has vested in interest. Until B reaches 25, the income generated by B’s share must be paid to B. (Note that B has _Saunders v Vautier_ rights so could choose to collapse their share before this).

C is a minor and until C reaches the age of 18 the trustees have the power (but not the obligation) to pay income to C’s parent or guardian (or otherwise apply it for C’s maintenance, education and benefit e.g., by paying school fees directly to the school). Income not used is accumulated.
```

S 31 is commonly expressly amended to defer a beneficiary's right to income, meaning they become entitled to both income and capital at the same time.

#### Power to Advance Capital

```ad-statute
title: s 32 TA 1925 - Power of advancement

(1) Trustees may at any time or times pay or apply any capital money subject to a trust, or transfer or apply any other property forming part of the capital of the trust property, for the advancement or benefit, in such manner as they may, in their absolute discretion, think fit, of any person entitled to the capital of the trust property or of any share thereof, whether absolutely or contingently on his attaining any specified age or on the occurrence of any other event, or subject to a gift over on his death under any specified age or on the occurrence of any other event, and whether in possession or in remainder or reversion, and such payment, transfer or application may be made notwithstanding that the interest of such person is liable to be defeated by the exercise of a power of appointment or revocation, or to be diminished by the increase of the class to which he belongs:

Provided that—

- (a) property (including any money) so paid, transferred or applied for the advancement or benefit of any person must not, altogether, represent more than the presumptive or vested share or interest of that person in the trust property; and
- (b) if that person is or becomes absolutely and indefeasibly entitled to a share in the trust property the money or other property so paid, transferred or applied shall be brought into account as part of such share; and
- (c) no such payment, transfer or application shall be made so as to prejudice any person entitled to any prior life or other interest, whether vested or contingent, in the money or other property paid, transferred or applied unless such person is in existence and of full age and consents in writing to such payment or application.
- (1A) In exercise of the foregoing power trustees may pay, transfer or apply money or other property on the basis (express or implied) that it shall be treated as a proportionate part of the capital out of which it was paid, transferred or applied, for the purpose of bringing it into account in accordance with proviso (b) to subsection (1) of this section.

(2) This section does not apply to capital money arising under the M1 Settled Land Act 1925.

(3) This section does not apply to trusts constituted or created before the commencement of this Act.
```

A beneficiary who expects to receive capital from a trust at a future date may wish to receive their capital before it vests in possession.

[s 32 TA 1925](https://www.legislation.gov.uk/ukpga/Geo5/15-16/19/section/32) gives trustees the power to use capital for the ‘advancement or benefit’ of a beneficiary before the beneficiary becomes absolutely entitled to the property.

The power of advancement:

- May be used by both adult and minor beneficiaries
- Applies to both vested and contingent interests
- Can be modified or excluded by the trust instrument: [s 69(2) TA 1925](https://www.legislation.gov.uk/ukpga/Geo5/15-16/19/section/69)

The trustees may use the power of advancement to pay up to 100% of a beneficiary’s entitlement before it vests at all (if the interest is contingent) or before it vests in possession (if the interest is vested in interest).

Because the exercise of the power may prejudice other beneficiaries, the power may only be exercised with the written consent of beneficiaries with a prior interest.

For example, if a trustee holds property on trust for A for life, remainder to B, the trustees can only exercise the power of advancement in favour of B with A’s written consent. This is because providing B with their capital early will clearly prejudice A.

- In the most extreme case, if B requests 100% of their capital, A’s life interest will be extinguished.
- Even if B requests less than 100% of their capital, this will reduce the value of A’s interest as there will be smaller capital fund from which to generate A’s income.

Consent can only be provided by beneficiaries who are of full age and sound mind.

#### Meaning of ‘advancement’

A key issue for trustees when deciding whether to exercise the power of advancement is whether this action will result in the advancement or benefit of the beneficiary. Over time the case law in this area has developed to recognise a broader meaning of advancement than its previous limitations to the areas of education, career and marriage.

Advancement has now been recognised to provide for an immediate financial benefit for a beneficiary, such as to avoid an inheritance tax liability, [[Pilkington v Inland Revenue Commissioners [1964] AC 612]]. In this case Viscount Radcliffe defined advancement as ‘any use of the money which will improve the material situation of the beneficiary’.

Subsequent case law indicates that the advancement of the beneficiary can include the improvement of the beneficiary’s moral well-being by giving the money for charitable purposes, but only to the extent that the beneficiary would have otherwise used their own resources for such purposes (see [[Re Clore’s Settlement Trusts [1966] 1 WLR 955]] and [[X v A [2006] 1 WLR 741]])_.

Trustees have a duty following the exercise of the power of advancement to ensure that the money is being used for the purposes that it was provided. Should the beneficiary be found to be spending the money on something else, the trustees should not pay any further money to the beneficiary. However, they may instead pay money directly to a third party for the advancement of the beneficiary instead.

In [[Re Pauling’s Settlement Trusts [1964] Ch 303]] the trust was managed by a bank with a power to advance property to the children of a marriage. The bank made a number of advancements to the children. These advancements were used for the benefit of the children’s parents rather than their own benefit, including the purchase of a house in the parents’ names. It was found that the trustees were obliged to check that the money had been applied for the purpose that it was advanced and not leave the recipients free to spend the money as they wished. The bank’s failure to do this was a breach of trust.

#### Bringing the Payment into Account

The trustees may use the power of advancement to pay up to 100% of a beneficiary’s [[beneficial entitlement]].

Any such payment must be brought into account when the beneficiary becomes absolutely entitled. In other words, the amount that the beneficiary will receive when their interest vests will be reduced proportionately to reflect the proportion of the capital that they received early.

Trustees have a choice between treating the share advanced as a **proportionate share of the overall trust value or its strict monetary value**. The choice they make could have significant consequences for both the beneficiary who receives the advancement and all the other beneficiaries. This is best illustrated by way of example.

```ad-example
Trustees hold a trust fund worth £20,000 on trust for A, B, C and D in equal shares when they reach 18. The trustees exercise the power of advancement to pay £5,000 to A. The trustees must choose whether this is to be treated as A's proportionate share of the fund. This could make a significant difference to A as £5,000 would amount to 100% of A's share in the trust fund at the date it was paid.

If the £5,000 is treated as A’s proportionate share, A will no longer be entitled to anything from the trust fund, regardless of how much the fund is worth when A reaches 18.

For example, if the fund grows to £25,000 this will be shared equally between B, C and D (£8,333 each).

If the £5,000 is not treated as A’s proportionate share, the trustees will take A’s payment into account before making their distributions, bringing the total trust value to £30,000. That is then shared equally between all four beneficiaries. B,C and D each receive £7,500. A has already had £5,000 so is entitled to an additional £2,500.
```

> [!summary]
> - Adult beneficiaries with vested interests in trust property will usually have a right to receive the trust income as it arises. Those with contingent interests will only have a right to income if their interest ‘carries the intermediate income’.
> - Minor beneficiaries will not usually have a right to income but the trustees have a statutory power under s 31 TA 1925 to pay the income to the beneficiary's parent or guardian, or apply it directly for the beneficiary’s maintenance, education or benefit. This gives the trustees a wide discretion
> - Income which is not paid to the beneficiaries before the age of 18 is accumulated and added to the capital.
> - Trustees also have a statutory power under s 32 TA 1925 to advance capital.
> - The power of advancement can be exercised in favour of any beneficiary, even if their interest is contingent, but requires the consent of beneficiaries with a prior interest.
> - The power of advancement must be used for their advancement or benefit.
> - Both powers may be modified or excluded by the trust instrument.

## Collecting Deceased's Assets

- PRs produce grant of representation to whoever is holding the various asset, and then collect them.
- For some assets, a grant is not required (e.g., realising assets under Administration of Estates (Small Payments) Act 1965).

Some properties do not devolve on the PRs:

- Life interest
- Joint tenancy
- Policy held in trust for others
- Pension schemes

## Funeral and Testamentary Expenses

- PR should pay outstanding debts and the funeral account as soon as monies can be collected/ realised
- May need to repay a loan from deceased's bank to pay IHT to obtain the grant.
	- Such a loan will probably have come with a 'first proceeds' undertaking.
- When considering which assets to sell, PRs should consider:
	1. Provisions of deceased's will
	2. Beneficiaries' wishes
	3. Tax consequences.

### Funeral Expenses

Reasonable funeral expenses are payable from the deceased's estate.

### Testamentary Expenses

These are expenses incident to the proper performance of the duties of a PR. Includes:

- Costs of obtaining grant
- Costs of collecting and preserving deceased's assets
- Costs of administering deceased's estate (solicitor and valuer fees)
- IHT payable on death of deceased's property in the UK which vests in the PRs (s 211 IHTA 1984).

### Solvent Estate

The statutory order for payment of debts is set out in AEA 1925, Sch 1, Part II (s 34(3) AEA 1925).

```ad-test
title: General rule
When choosing assets to pay funeral/ testamentary expenses and debts, assets forming part of the reside are to be used before property given to specific legatees. 
```

#### Subject to

The above order is subject to:

- s 35 AEA 1925: a beneficiary who takes an asset which is security for a debt takes the asset subject to the debt.
- The will can vary ss 34(3) & 35 – check for any provisions.

### Insolvent Estate

```ad-defn
An estate is insolvent if the assets are insufficient to discharge in full the funeral, testamentary and administration expenses, debts and liabilities.
```

In doubtful cases, PRs should administer the estate as if it is insolvent. For an insolvent estate being administered out of court, follow the order of distribution in Administration of Insolvent Estates of Deceased Persons Order 1986.

## Paying Legacies

Step 2; consider discharging the gifts arising on death, other than gifts of the residuary estate. Consider making interim distributions to the residuary beneficiaries.

### Specific Legacies

- Methods of transferring the property to the beneficiary/ trustee will vary
	- The legal estate in a house or flat should be vested in a beneficiary by an 'assent'.
- In the case of specific gifts (only), the vesting of the asset in the beneficiary is retrospective to the date of death, so that any income produced by the property.
	- Beneficiary is not entitled to the income as it arises, but must wait for the PR to vest the property in the beneficiary.
- Costs of transferring the property to a legatee and cost of insurance cover taken are the responsibility of the legatee, who should reimburse the PR.

### Pecuniary Legacies

The will may specify an intention to pay the legacy, e.g., from the residuary estate. Where the will makes no such provision for pecuniary legacies, they are paid primarily from residuary personalty.

#### Time for Payment

- General rule
	- Pecuniary legacy payable at the end of “the executor's year”: one year after testator's death.
	- s 44 EA 1925: PRs are not bound to distribute the estate before the expiration of one year from the death.
- 4 occasions where interest is payable on a pecuniary legacy from the date of death:
	1. Legacy payable in satisfaction of debt owed to a creditor
	2. Legacy charged on land owned by testator
	3. Legacy payable to the testator's minor child
	4. Legacy payable to any minor where the intention is to provide for the maintenance of that minor.

## Administration and Distribution

Before drawing up estate accounts and making a final distribution of residue, the PRs should deal with IHT liability and taxes.

### Adjusting IHT Assessment

The amount of IHT payable may have to be adjusted since the IHT account was submitted:

- Discovery of additional assets/ liabilities
- Discovery of lifetime transfers
- Agreement of provisionally estimated values
- Agreement between PRs and HMRC of a tax liability or repayment
- “Loss relief” from sales made by PRs after deceased's death.

#### IHT Loss Relief

PRs often force to sell assets to raise cash to pay for debts, tax liabilities or legacies. If PRs end up selling assets for less than their value at the date of death, they can claim loss on sale relief.

```ad-important
Where ‘qualifying investments’ are sold within 12 months of death for less than their market value at the date of death (ie ‘probate value’) then the sale price may be substituted for the market value at death and the IHT liability adjusted accordingly (IHTA 1984, ss 178–189).
```

- ‘Qualifying investments’ are shares or securities which are quoted on a recognised stock exchange at the date of death, and also holdings in authorised unit trusts.
- Relief is not automatic; must be claimed.
- Available only when PR makes the sale, not when the beneficiary does.
- If relief claimed, value of qualifying investments at death must be reduced for CGT purposes (s 187).
	- So never claim the relief if the estate is passing to a surviving spouse/ civil partner.

#### Limitation

To stop PRs selling shares to create a loss and then either buying them back (‘bed and breakfasting’) or reinvesting the proceeds in other shares, s 180 restricts the relief where the appropriate person buys new qualifying investments within the period starting with death and ending two months after the date of the last sale.

ss 190-198: provisions allowing loss relief in relation to the sale of land within 4 years of a death at a loss.

### Continuing IHT Liability

#### IHT Instalments

- If PRs opted to pay IHT by instalments, they continue to be liable until all instalments have been paid.
- So don't transfer all the assets to the beneficiaries.

#### IHT on Lifetime Transfers

- General rule: donees of lifetime transfers are primarily liable for the tax. P
- Rs of the donor’s estate may become liable if the tax remains unpaid by the donees 12 months after the end of the month in which the donor died.
- PRs’ liability is limited to the extent of the deceased’s assets which they have received, or would have received in the administration of the estate, but for their neglect or default.
- If the deceased gave away property during their lifetime but reserved a benefit in that property, such property is treated as part of their estate on death.
	- The same procedure applies: PRs liable if tax remains unpaid after 12 months.

### Corrective Account

Submit Form C4 to HMRC to report all variations to assets/ liabilities and reliefs.

### IHT Clearance

PRs will want to obtain confirmation from HMRC that there is no further claim to IHT. Effects:

- Discharges the PRs and all other persons from further liability to IHT (unless there is fraud/ non-disclosure of material facts).
- Extinguishes any charge imposed by HMRC on deceased's property.

HMRC must apply for a clearance certificate using form IHT30. They will reply with a letter certifying the discharge.

### Income Tax and CGT

#### Deceased's Liability

```ad-action
Immediately following the death, the PRs must make a return to HMRC of the income and capital gains of the deceased for the period starting on 6 April before the death and ending with the date of death.
```

- Any liability to tax is a debt of the deceased, to be paid by PRs during administration.
- Any tax refund represents an asset.

#### Administration Period

For each income tax year (or part) during the administration period, the PRs must calculate their income tax and CGT liability on assets disposed of for administration purposes.

#### Paying Income Tax & CGT

PRs can make a **one-off informal payment** of all income tax and CGT at the end of administration, unless the estate is classified as a complex estate.

```ad-defn
title: Complex estate
An estate is considered complex if either: 
1. the value of the estate exceeds £2.5 million; or 
2. tax due for the whole of the administration period exceeds £10,000; or 
3. the value of assets sold in a tax year exceeds £500,000.
```

##### Exception

UK residential land must be paid within a short period of completion of the sale.

#### Income Tax

The rules of income tax for PRs are special:

- No higher rate of income tax
- No personal savings and dividend allowance
- There is still a personal allowance.

| Asset        | Rate of tax |
| ------------ | ----------- |
| Dividends    | 8.75%       |
| Other income | 20%         |

##### ISAs

Investments held in an ISA wrapper will not be liable to income tax (or CGT) during the administration of the deceased’s estate, or three years from the death, whichever is the shorter. PRs will, therefore, pay no tax during that period on the deceased’s ISA investments.

##### Concession

If the only income is interest and the interest does not exceed £500, PRs pay no income tax.

#### Relief

If PRs take out a bank loan to pay the IHT on the deceased's personal property in the UK in order to obtain a grant, relief can be claimed on any interest paid on the bank loan.

#### Beneficiary's Income Tax Liability

After PR's income tax position settled, net income will be paid to the beneficiary. The beneficiary must report the grossed up amount of this income in their income tax return.

PRs must supply beneficiary with Form R185 - certificate of deduction of tax. Beneficiaries whose income, including the estate income, is not above the level of the personal allowance or the savings or dividend allowances can reclaim the tax paid.

### Capital Gains Tax

- On death, there is no disposal for CGT purposes, so no liability arises.
- If PRs dispose of chargeable assets during the administration of the estate to raise cash, they are liable to CGT on an chargeable gains they make (except ISAs)
- Rate is 20%, or 28% for residential property.
- PRs may also deduct from the disposal consideration the incidental cost of the disposal, and a proportion of the cost of valuing the deceased's estate for probation purposes.
- PRs may claim the annual exemption for the tax year in which the deceased's died, and the following two years (if the administration lasts this long).
- Exemption of £12,300/ year
	- The PRs could plan asset sales carefully to realise gains in stages for each tax year it is available.

#### Sale at a Loss

An allowable loss for CGT will arise if PRs sell assets for less than their value at death. The loss may be relieved by setting it against gains in the same or any future tax year by the PRs. Plan sales carefully.

#### Accelerated CGT Payment on UK Residential Land

Finance Act 2019, s 14 & Sch 2: accelerated reporting and payment dates for CGT on UK land disposed of by non-residents. Return and payment must be submitted within 60 days of the disposal.

The charge extends to all disposals of UK residential land on/ after 6 April 2020, but only where tax is due. The tax is paid using an approximation of the level of income expected during the year. The payment is made on account of the tax due at the end of the year.

#### Transfer of Assets to Legatees

If PRs vest the assets in the legatees rather than selling them, no chargeable gain or allowable loss arises. The beneficiary or trustee is assumed to acquire the asset transferred at its probate value.

### Transfer of Assets to Residuary Beneficiaries

If there have been interim distributions to certain beneficiaries, these should be taken into account when determining the transfer of remaining assets to the residuary beneficiaries .

| Entitlement | Adult                                                                                            | Minor                                                                                                                                                                                                              |
| ----------- | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Vested      | Entitlement can be transferred to them.                                                          | Property usually held on trust until age of majority reached. May be possible to transfer minor's beneficial entitlement if expressly authorised in the will, or to parents/ guardians on the behalf of the minor. |
| Contingent  | Property must be transferred to trustees to hold on their behalf until contingency is satisfied. | Property held on trust until age of majority reached and/or contingency satisfied.                                                                                                                                 |

#### Personal Property

The PRs indicate that they no longer require property for administration purposes when they pass title to it by means of an assent. Note that the beneficiary's title to the property derives form the will. The assent just gives effect to the gift by the PRs.

Company shares are transferred y share transfer form, unless held by a nominee company (as is often the case).

#### Freehold/ Leasehold Property

Personal representatives vest the legal estate in land in the person entitled (whether beneficially or as trustee) by means of an assent, which will then become a document of title to the legal estate.

```ad-tip
If PRs continue to hold the property in their changed capacity as trustees, PRs should 'assent' to this to formally vest the legal estate in themselves as trustees. 
```

#### Assent Formalities

```ad-statute
title: s 36(4) AEA 1925
An assent to the vesting of a legal estate shall be in writing, signed by the personal representative, and shall name the person in whose favour it is given and shall operate to vest in that person the legal estate to which it relates; and an assent not in writing or not in favour of a named person shall not be effectual to pass a legal estate.
```

The Land Registration Rules 2003 specify the form of an assent further.

Any person in whose favour the PRs make an assent or conveyance may require notice of it to  
be endorsed on the original grant of probate or administration. It is good practice to make this endorsement routinely at the same time as giving the assent.

If title to the land is registered, 2 options for the PRs:

- Apply to be registered as proprietor in place of the deceased.
	- PRs produce grant of representation when making application.
- Transfer the property by assent without being registered as proprietor.
	- Beneficiary must be given a certified copy of the grant of representation, to present with their application for registration.

### Estate Accounts

PRs must produce estate accounts for the residuary beneficiaries. Purpose: to show all the assets of the estate, the payment of debts, administration expenses and legacies and balance remaining for residuary beneficiaries.

The residuary beneficiaries sign the accounts to indicate approval -> releases PRs from further liability.
