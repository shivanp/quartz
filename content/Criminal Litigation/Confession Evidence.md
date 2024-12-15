---
aliases: 
tags: 
date created: Thursday, September 1st 2022, 9:11:11 pm
date modified: Sunday, December 10th 2023, 12:40:00 am
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

# Confession Evidence

```toc
```

## Definition

> [!defn] Confession
> Any statement wholly or partly adverse to the person who made it, whether made to a person in authority or not and whether made in words or otherwise (s 82(1) PACE 1984).

## Admissibility

### Confessions

> [!statute] s 76(1) PACE 1984
> In any proceedings a confession made by an accused person may be given in evidence against him in so far as it is relevant to any matter in issue in the proceedings and is not excluded by the court in pursuance of this section.

Proposition: A **pre-trial confession** is admissible in trial to prove D's guilt.

Proof:

- A confession made by D before trial which is repeated in evidence at his trial will be hearsay.
- Such a confession is admissible in evidence by virtue of s 114(1)(a) of the CJA 2003, which provides that hearsay evidence will be admissible at trial if it is made admissible by virtue of any statutory provision.
- Confession evidence is made admissible by s 76(1) of PACE 1984.

### Mixed Statements

A confession may include a statement favourable to D. The whole statement will be admissible under s 76(1) as an exception to the rule excluding [[Hearsay Evidence]].

### Confessions and a Co-accused

Consider a defendant $D$ and co-defendant $D_c$.

1. Any evidence given by $D_c$ **at trial** which implicates $D$ (including a confession made by $D_c$) will be admissible in evidence against $D$.
2. If $D_c$ has **pleaded guilty** at an earlier hearing and is giving evidence for the prosecution **at $D$'s trial**, any evidence he gives implicating $D$ in the commission of the offence will be admissible in evidence against $D$.
3. A **pre-trial** confession by $D_c$ may be admissible against $D$
	- Used to be inadmissible under common law
	- [[R v Y [2008] EWCA Crim 10]]: admissible hearsay because in the interests of justice for such evidence to be admitted.
4. Where two (or more) co-defendants are pleading not guilty and are **tried jointly**, s 76A(1) PACE 1984 allows one defendant to adduce in evidence the fact that a co-defendant has made a confession.

## Challenging Admissibility – S 76

D can challenge the admissibility of a confession by arguing:

1. Confession was not made/ fabricated/ misheard; or
2. Confession was made but was untrue. It was made for reasons other than admitting guilt.

If challenging on ground (2), use

> [!statute] s 72(2) PACE 1984
> If, in any proceedings where the prosecution proposes to give in evidence a confession made by an accused person, it is represented to the court that the confession was or may have been obtained—
> - (a) by **oppression** of the person who made it; or
> - (b) in consequence of **anything said or done** which was likely, in the circumstances existing at the time, to render **unreliable** any confession which might be made by him in consequence thereof,
> 
> the court shall not allow the confession to be given in evidence against him except in so far as the prosecution proves to the court beyond reasonable doubt that the confession (notwithstanding that it may be true) was not obtained as aforesaid. 

If this is raised, the burden of proof is on the prosecution to show beyond a reasonable doubt that the confession was not so obtained.

### Oppression

“Oppression” includes torture, inhuman or degrading treatment, and the use or threat of violence (whether or not amounting to torture) – s 76(8). Unusual for this to be argued.

### Unreliability

Although s 76(2)(b) does not require deliberate misconduct on the part of the police, the thing which is said or done will usually involve an alleged breach of Code C.

> [!example]
> - Denying a suspect refreshments/ rest between interviews
> - Offering a suspect an inducement to confess
> - Misrepresentating the strength of the prosecution case
> - Questioning a suspect in an inappropriate way
> - Questioning a suspect who the police should have known was not in a fit state to be interviewed
> - Threatening a suspect.

> [!question] Being denied access to legal advice
> - Being denied access to legal advice at the police station is a breach of Code C and s 58 PACE 1984. 
> - This will not alone lead to the exclusion of the confession
> - Must be a **causal link** between the breach and the unreliability of the confession subsequently made ("but for" test)

Note that the causal link is needed for any unreliability argument, not just legal advice.

### Co-defendant Confession Evidence

> [!statute] s 76A PACE 1984 - Confessions may be given in evidence for co-accused
> (1) In any proceedings a **confession made by an accused** person may be given **in evidence for another** person charged in the same proceedings (a co-accused) in so far as it is relevant to any matter in issue in the proceedings and is **not excluded** by the court in pursuance of this section.
> 
> (2) If, in any proceedings where a co-accused proposes to give in evidence a confession made by an accused person, it is represented to the court that the confession was or may have been obtained—
> - (a) by oppression of the person who made it; or
> - (b) in consequence of anything said or done which was likely, in the circumstances existing at the time, to render **unreliable** any confession which might be made by him in consequence thereof,
> 
> the court shall **not allow** the confession to be given in evidence for the co-accused except in so far as it is proved to the court on the **balance of probabilities** that the confession (notwithstanding that it may be true) was **not so obtained**.

## Challenging Admissibility – S 78

> [!statute] s 78 PACE 1984 - Exclusion of unfair evidence
> (1) In any proceedings the court may **refuse to allow evidence** on which the prosecution proposes to rely to be given if it appears to the court that, having regard to all the circumstances, including the circumstances in which the evidence was obtained, the admission of the evidence would have such an adverse effect on the **fairness of the proceedings** that the court ought not to admit it.
> 
> (2) Nothing in this section shall prejudice any rule of law requiring a court to exclude evidence.

This provides the court with the discretion to exclude confession evidence.

### D Admits Making Confession

Where D admits making the confession but alleges that the police breached PACE 1984/ Codes of Practice in obtaining the confession, the court will exclude the confession under s 78 only if the breaches are significant and substantial ([[R v Walsh (1989) 91 Cr App R 161]]).

Note the overlap between s 76(2)(b) and s 78. Generally, the court has exercised discretion under s 78 with suspects denied access to legal advice.

s 78 is broader, and may also be used when:

- The physical condition of D makes the confession unreliable
- D has an ulterior motive for making a confession (e.g., wanting to protect someone).

### D Denies Making Confession

A confession allegedly made by D outside the police station is likely to be excluded under s 78 if the police breached Code C by:

- Failing to make an accurate record of D's comments (Code C, para 11.7(a))
- Failing to give D an opportunity to view the record and sign for/ dispute accuracy (Code C, para 11.11)
- Failing to put admission/ confession to D at the start of his subsequent police station interview (Code C, para 11.4).

## Flowchart

![[confession-evidence.png]]
