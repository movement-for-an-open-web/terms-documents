[![Movement for an Open Web](https://movementforanopenweb.com/wp-content/uploads/2021/09/MOW-LOGO_MOW-HORIZONTAL.svg)](https://movementforanopenweb.com)

FREQUENTLY ASKED QUESTIONS FOR THE SEARCH ONLY TERMS CONTRACT

**DISCLAIMER**

*This FAQ is provided for general informational purposes only and is not legal
advice. It is intended to give an overview of the Search Only Terms Contract:
for Access and Use of Website (the “Contract”), but it does not replace or
modify the Contract itself.*

*The Contract is the legally binding document governing access to and use of
Website Content. In the event of any inconsistency between this FAQ and the
Contract, the Contract shall prevail.*

*Application and enforcement of the Contract will depend on the specific
circumstances of each case, including the nature of the Accessing Party, the
method of access, and the relevant jurisdiction. Enforcement options, including
litigation, may not be appropriate in all situations and should be considered on
a case-by-case basis.*

*Publishers should seek independent legal advice where necessary, particularly
in relation to implementation, enforcement strategy, and cross-border issues.*

*Nothing in this FAQ limits or waives any rights or remedies available to the
Website Operator under the Contract or applicable law.*

*For the full terms, see the [Contract](2.txt).*

**Table of Contents**

<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=3 orderedList=false} -->

<!-- code_chunk_output -->

- [INTRODUCTORY QUESTIONS](#introductory-questions)
  - [What is this contract?](#what-is-this-contract)
  - [Why does it exist?](#why-does-it-exist)
  - [Who does it apply to?](#who-does-it-apply-to)
  - [How does it work (step by step)?](#how-does-it-work-step-by-step)
    - [Legal layer (the contract itself)](#legal-layer-the-contract-itself)
    - [Technical layer (machine-readable signals)](#technical-layer-machine-readable-signals)
    - [Alignment between the two](#alignment-between-the-two)
  - [Works alongside other website policies](#works-alongside-other-website-policies)
  - [How do I apply this to my Website?](#how-do-i-apply-this-to-my-website)
- [Frequently Asked Questions](#frequently-asked-questions)
  - [GENERAL](#general)
    - [Why does the Movement for an Open Web (MOW) site not implement this Contract?](#why-does-the-movement-for-an-open-web-mow-site-not-implement-this-contract)
  - [CONTRACT TERMS](#contract-terms)
    - [Is this contract binding if the accessing party never expressly agrees to the Contract?](#is-this-contract-binding-if-the-accessing-party-never-expressly-agrees-to-the-contract)
    - [Does allowing search engine indexing weakens the restriction on AI use?](#does-allowing-search-engine-indexing-weakens-the-restriction-on-ai-use)
    - [How does this interact with existing “free-to-index” norms?](#how-does-this-interact-with-existing-free-to-index-norms)
    - [How is this Contract incorporated into other terms or systems?](#how-is-this-contract-incorporated-into-other-terms-or-systems)
    - [What happens if this Contract conflicts with other terms?](#what-happens-if-this-contract-conflicts-with-other-terms)
    - [Why do different terms sometimes apply to different consumers or services?](#why-do-different-terms-sometimes-apply-to-different-consumers-or-services)
    - [Why is this Contract necessary alongside existing copyright law?](#why-is-this-contract-necessary-alongside-existing-copyright-law)
  - [SCRAPING, CRAWLING & TECHNICAL CONTROL](#scraping-crawling--technical-control)
    - [How do you prove that scraping or AI training has taken place?](#how-do-you-prove-that-scraping-or-ai-training-has-taken-place)
    - [Does the “disallow everything” language in robots.txt risk unintentionally blocking search engine access?](#does-the-disallow-everything-language-in-robotstxt-risk-unintentionally-blocking-search-engine-access)
    - [How should publishers practically evidence repeated infringement at scale?](#how-should-publishers-practically-evidence-repeated-infringement-at-scale)
    - [How do we address AI companies relying on third-party scrapers?](#how-do-we-address-ai-companies-relying-on-third-party-scrapers)
    - [What infrastructure is needed to monitor infringement?](#what-infrastructure-is-needed-to-monitor-infringement)
    - [Can token-based or cryptographic systems realistically track content use?](#can-token-based-or-cryptographic-systems-realistically-track-content-use)
    - [What role do data label Terms Document Locators (TDLs) and technical standards play?](#what-role-do-data-label-terms-document-locators-tdls-and-technical-standards-play)
    - [Does this Contract prevent accessibility tools or assistive technologies (e.g. screen readers)?](#does-this-contract-prevent-accessibility-tools-or-assistive-technologies-eg-screen-readers)
    - [How should robots.txt and technical signals be interpreted?](#how-should-robotstxt-and-technical-signals-be-interpreted)
    - [Do changes need to be made to HTML?](#do-changes-need-to-be-made-to-html)
    - [Can websites covered by this Contract be used in Common Crawl?](#can-websites-covered-by-this-contract-be-used-in-common-crawl)
    - [Can websites covered by this Contract be added to the Internet Archive?](#can-websites-covered-by-this-contract-be-added-to-the-internet-archive)
  - [COMPENSATION & COMMERCIAL USE](#compensation--commercial-use)
    - [How should pricing be approached given the variability in content value?](#how-should-pricing-be-approached-given-the-variability-in-content-value)
    - [Would introducing payment expectations undermine free search visibility?](#would-introducing-payment-expectations-undermine-free-search-visibility)
  - [ENFORCEMENT & LITIGATION](#enforcement--litigation)
    - [What happens if a company simply ignores the Contract and operates outside the UK?](#what-happens-if-a-company-simply-ignores-the-contract-and-operates-outside-the-uk)
    - [Is it viable to bring multiple small claims for repeated infringements?](#is-it-viable-to-bring-multiple-small-claims-for-repeated-infringements)
    - [What is the most effective litigation pathway if cases escalate?](#what-is-the-most-effective-litigation-pathway-if-cases-escalate)
    - [Should enforcement prioritise an early test case?](#should-enforcement-prioritise-an-early-test-case)
    - [Would a collective enforcement model be more effective?](#would-a-collective-enforcement-model-be-more-effective)
    - [Should enforcement go through regulators rather than courts?](#should-enforcement-go-through-regulators-rather-than-courts)
    - [Is there a risk of retaliation from search engines or platforms?](#is-there-a-risk-of-retaliation-from-search-engines-or-platforms)
  - [CONTRACT ECOSYSTEM AND ADOPTION](#contract-ecosystem-and-adoption)
    - [What is the role of a central coordinating body (e.g. Movement for an Open Web)?](#what-is-the-role-of-a-central-coordinating-body-eg-movement-for-an-open-web)
    - [Will adoption be standardised across publishers and jurisdictions?](#will-adoption-be-standardised-across-publishers-and-jurisdictions)

<!-- /code_chunk_output -->

# INTRODUCTORY QUESTIONS

## What is this contract?

This contract governs how your website content may be accessed and used.

The Contract also establishes a default Access Fee of £500 per discrete
“Product” accessed as a result of an Access Event, which is automatically
incurred each time a Product is accessed outside the unwaived permitted licensed
scope. This fee is conditionally waived only where the access falls strictly
within permitted Licensed Access (such as Non-Commercial Use or Search Indexing)
and all contractual conditions are met. Any failure to meet those conditions
results in the Access Fee becoming immediately due.

It applies to all forms of access, from ordinary human browsing, to search
engine crawling and indexing, and sets clear limits on how that content may be
reused.

In particular, it permits search indexing only, while restricting scraping, bulk
extraction, dataset creation, and any AI-related use unless expressly authorised.

It operates alongside any general website terms (such as terms of use or cookie
policies), but is focused specifically on content access, indexing, and
downstream reuse, including automated and AI-driven activity.

## Why does it exist?

This contract exists to draw a clear boundary between what is permitted and what
requires permission.

It allows standard search engine indexing so the website can be discovered,
while making clear that activities such as AI training, dataset creation, bulk
scraping, or other datadriven reuse are not included in that permission.

Historically, these uses have often been treated as overlapping or implicit.
This contract removes that ambiguity by expressly separating ordinary search
indexing from AI and data-extraction activities and treating the latter as
controlled uses that require explicit authorisation.

## Who does it apply to?

This contract applies to any person, entity, or system that accesses or
interacts with the website or its content, regardless of the method or
technology used.

It covers access by:

- individual human users,
- companies and other organisations,
- search engines,
- automated crawlers and bots, and
- Artificial Intelligence Systems or machine-driven agents.

It applies equally whether access is:

- manual, such as a person visiting pages through a browser, or
- automated, such as bots, scrapers, crawlers, indexing tools, or AI-driven
  systems.

The intention is that there are no gaps or grey areas. If a person, company,
program, or system in any way accesses, retrieves, processes, or interacts with
the website or its content, that access falls within the scope of this contract
and is governed by its terms.

## How does it work (step by step)?

Think of it as working in layers — both legal and technical — at the same time:

### Legal layer (the contract itself)
   The Contract is made visible on the website, for example through integration
   via a link into website terms of service (sometimes called Terms and
   Conditions, or Website Terms etc.) or as an additional legal footer link or
   an on-page notice.

Please see “How do I apply this Contract” question below for how to apply the
Contract on your Website.

The Contract clearly states that anyone who accesses or uses the website is
subject to its rules.

Acceptance does not require a tick box or signature. Instead, agreement is
formed through conduct, simply by accessing, viewing, crawling, indexing, or
otherwise interacting with the website or its content.

This ensures that:

- the terms apply automatically, and
- no user or system can argue that they were unaware of the terms.

### Technical layer (machine-readable signals)

Alongside the legal contract,
the website uses technical, machine-readable links to the Contract to communicate
permissions and restrictions to automated systems.

These may include:

- robots.txt files,
- HTTP headers, and
- other standard machine-readable signals.

These signals tell automated systems — such as crawlers, bots, and AI systems —
the location of the Contract which defines what they are allowed to do and what
they are not allowed to do when accessing the website. As many websites use the
same location for the Contract it is machine-readable and can be readily
identified across many websites.

### Alignment between the two

The legal terms and the technical instructions are intentionally designed to say
the same thing.

For example:

- search engines are permitted to crawl content strictly for search indexing and
  discovery;
- AI systems and dataharvesting tools are not permitted to ingest content for
  training, datasets, or other AI-related uses without gaining explicit
  additional permission.

Because the legal rules and technical signals are aligned, there is no ambiguity
about permitted use. This significantly strengthens enforcement, as a user or
system has been put on notice in more than one way.

## Works alongside other website policies

This Contract does not replace any existing website policies. Instead, it
operates alongside them, each addressing a different aspect of how the website
is run and used.

In the same way as:

- cookie policies explain how cookies and tracking technologies are used,
- privacy notices explain how personal data is handled, and
- general terms of use set out the overall rules for using the site,

this contract focuses specifically on how website content may be accessed,
indexed, and reused, particularly by automated systems and AI-driven
technologies.

## How do I apply this to my Website?

**How to implement the** Search Only Terms Contract: for Access and Use of
Website (the “**Contract**”) **(Publisher instructions)**

Please follow the steps below to correctly implement the Contract on your
website.

**1. Use the official MOW URL (no self-hosting required)**

You must not create or host your own version of the Contract as the Contract is
hosted and managed exclusively by MOW.

Each version of the Contract is assigned a unique, fixed URL
(<https://m4ow.uk/socw/2.txt>), which is stewarded by MOW.

Once published the content at a given URL must never be changed. If any
amendment is required, a new version will be created and assigned a new URL
(e.g. /2.txt, /3.txt, etc.). Updates versions will be published on the MOW
website (<https://movementforanopenweb.com/>).

**2. Update robots.txt file**

Next, add the following lines to the website’s robots.txt file (this file is
usually located at: yourdomain.com/robots.txt):

```plain
# License https://m4ow.uk/socw/2.txt
User-agent: *
tdl: https://m4ow.uk/socw/2.txt
Allow: /
```

This step ensures all crawlers are explicitly informed that access is governed
by the Contract.

**3. Link in your Terms & Conditions**

You should include a reference to the Search Only Terms Contract: for Access and
Use of Website into your terms governing use of your website (for example, your
website Terms and Conditions or Legal Notice).

To validly incorporate the Contract into your website terms and conditions, you
should insert the following wording below into your website terms to formally
incorporate the contract terms.

**(A) Mandatory wording – adoption of the Contract**

**Insert the following text in the relevant place in your website terms and
conditions**

[*Clause 1 – insert relevant clause number in line with your website terms and
conditions*] These [*terms of service\* use the name of the legal terms you
offer on our website*] refers and incorporates the following additional terms,
which also apply to your use of our [*site- use the same term you use on your
terms for your website*]:

[Clause 1.1] Our Search Only Terms Contract: for Access and Use of Website
(available at the version-controlled URL published by MOW, currently being the
following link: <https://m4ow.uk/socw/2.txt>) governs crawling, indexing and
other automated or programmatic access to the Website and its content.

[Clause 1.2] If there is an inconsistency between any of the provisions of these
[Terms and Conditions] and the provisions of [Search Only Terms Contract: for
Access and Use of Website as linked above], the provisions of the Search Only
Terms Contract: for Access and Use of Website, the version hosted at the
referenced MOW URL shall prevail.

**(B) Optional wording – override of cost of breach (Clause 14 only)**

*(Insert only if you wish to apply a different contractual sum for small claims
for breach of contract per [Clause 14]* Binding Search Only Contract for Access
and Use of Website)*

**Optional insert – Clause 14 (Cost of Breach) Override**

Clause 14 of the Contract (relating to fixed sums, minimum amounts or deemed
charges for unauthorised or unlicensed access) continues to expressly apply for
the purposes of this [*Website*] except for only the sum to be claimed for
breach of the terms by **Unlicensed Access by an Unlicenced User** which is to
be replaced by the amount [*£X being [amount in text] GBP*] per instance of
unauthorised or unlicensed access, as set out in the incorporated Binding Search
Only Contract for Access and Use of Website.

For the avoidance of doubt, all other provisions of the Contract continue to
apply without modification.

**4. Record the change for evidence (important)**

To create a record that this Contract was active at a specific point in time,
you should archive your robots.txt file after updating it.

A simple way to do this is using the Internet Archive (Wayback Machine):

- Go to: [https://web.archive.org](https://web.archive.org/)
- Enter: <https://yourdomain.com/robots.txt> into the "Save Page Now” text box
  and press the Save Page button
- Save a snapshot

This provides timestamped proof that the instruction existed at that date.

# Frequently Asked Questions

## GENERAL

### Why does the Movement for an Open Web (MOW) site not implement this Contract?

**Answer**: MOW is a not-for-profit that needs to make content available for AI
training, so AI responses are informed by alternative positions and arguments
from those presented by AI vendors and Big Tech. As such the Contract is not
compatible with the purpose of the MOW website.

## CONTRACT TERMS

### Is this contract binding if the accessing party never expressly agrees to the Contract?

**Answer:**

Short answer:

Yes. The Contract still applies.

Longer explanation:

When someone visits or uses the website after being clearly told there is a
Contract governing access, the law generally treats that as acceptance. This
approach is widely used across the web. You do not need a pop up or tick box for
the rules to apply. What matters is that the rules are clearly stated and the
user chooses to go ahead anyway.

*LEGAL NOTE – why wording matters*

*The phrases “by accessing or using” and “governing access and use” are
critical.*

*These link the Contract to conduct, not express consent.*

*Avoid softening this to “we ask users to comply” or “this sets expectations” —
that risks undermining the contractual footing.*

**Isn’t this just trying to contract around copyright limits (e.g. fair dealing
or fair use)?**

**Answer:** The Contract doesn’t replace copyright law. Instead, it sets
conditions for using the website that sit alongside the regulatory copyright
system. Just as venues can impose rules even where the law allows entry, a
website can limit how its content is used as a condition of access.

*LEGAL NOTE*

*Keep language that says the Contract “sits alongside statutory rights”.*

*Do not say “overrides” or “takes precedence over” copyright law — that invites
challenge.*

*The word “contractual” is important here.*

### Does allowing search engine indexing weakens the restriction on AI use?

**Answer:** No. The Contract clearly distinguishes between permitted “Index
Access” for search functionality. Search engines are allowed to look at pages so
they can point visitors to the original site. What they are not allowed to do is
reuse the content for AI training, summaries, or datasets. Permission is given
for one narrow purpose only.

Why this may come up: The distinction between search indexing and AI use is
increasingly blurred (particularly with large platforms), so this is a likely
point of confusion.

*LEGAL NOTE*

*The distinction between “indexing” and “AI training / datasets” is
foundational.*

*The phrase “purposelimited” is important — don’t replace it with vague wording
like “generally allowed”.*

### How does this interact with existing “free-to-index” norms?

**Answer:** It builds on them for search. Free indexing is preserved as a
baseline. The Contract just clarifies that AI and reuse are separate activities
requiring permission. The Contract preserves standard search indexing as a
baseline, while making clear that other forms of reuse—particularly AI-related
uses—are separate and require express permission which the Website Operator can
negotiate with the AI company separately to the Contract.

### How is this Contract incorporated into other terms or systems?

**Answer:**

This Contract may be incorporated into other contractual or technical frameworks
in several ways, depending on the system used by the Website Operator. These may
include:

1. robots.txt or equivalent machine-readable directives, which communicate the
   primary location of the Contract defined as a link;
2. legal footers or notices displayed on the Website, which set out binding
   terms of access;
3. terms and conditions or contractual documents, where this Contract is
   referenced as governing specific categories of use (for example, indexing,
   crawling, or content access).

Where incorporation occurs, it is intended that this Contract applies
specifically to licensed access for indexing and permitted crawling activities,
as defined herein.

*LEGAL NOTE:*

*This preserves flexibility. The key is that incorporation is multi-channel
(technical + contractual + notice-based) and not dependent on a single
mechanism.*

### What happens if this Contract conflicts with other terms?

**Answer:**

Where this Contract is incorporated into another agreement or set of terms, it
is intended to govern the specific subject matter of Website Content access,
indexing, crawling, and reuse for AI or data-related purposes.

In the event of any conflict:

- This Contract governs permitted crawling, indexing, and content reuse
  conditions for those activities;
- Other contractual terms may govern different aspects of the relationship (such
  as paid services, accounts, or paywalled content);
- Any apparent inconsistency should be interpreted so that both sets of terms
  operate harmoniously where possible, but this Contract remains determinative
  for content access and reuse permissions unless expressly stated otherwise in
  writing by the Website Operator.

*LEGAL NOTE:*

*This avoids overreach. The Website Operator is not claiming universal supremacy
over all contracts, only subject-matter primacy for indexing/AI/data use. That
is much more defensible.*

### Why do different terms sometimes apply to different consumers or services?

**Answer:**

The Website may operate different layers of terms depending on the type of user
or access method. For example:

- General consumers accessing public pages for non-commercial use may be subject
  to this Contract for browsing and indexing conditions;
- Registered consumers, subscribers, or paying consumers may also be subject to
  additional contractual terms (such as paywalls or service agreements);
- Automated systems such as search engine crawlers are subject to specific
  permissions relating to indexing and permitted crawling activity.
- This reflects the fact that not all access is identical, and different legal
  frameworks may apply depending on how the Website is used.

*LEGAL NOTE:*

*This addresses a common concern that applying different terms could create
inconsistency or confusion. In reality, the Contract applies a single legal
framework, but distinguishes between different types of access and use (e.g.
Non-Commercial Use, Search Indexing, and prohibited AI/data uses).*

*The distinction is use-based, meaning the same rules apply but different
conditions are triggered depending on how the Website Content is accessed. This
avoids overreach, removes ambiguity, and strengthens enforceability by ensuring
the Contract is clear.*

### Why is this Contract necessary alongside existing copyright law?

**Answer:**

This Contract does not replace or override copyright law. Instead, it sets out
additional contractual conditions for access and use of Website Content.

This means:

- Copyright law continues to apply independently;
- This Contract governs the conditions under which access is granted;
- Certain uses (such as indexing for search engines) are permitted, while other
  uses (such as AI training or dataset creation) require separate permission;
  and
- Rapid action can be taken via cost effective legal means (see later).

*LEGAL NOTE:*

*This preserves the critical distinction: contractual licence + statutory
copyright coexistence. Do not blur them.*

## SCRAPING, CRAWLING & TECHNICAL CONTROL

### How do you prove that scraping or AI training has taken place?

**Answer:** Content can carry hidden identifiers or patterns that show up later
inside AI outputs or datasets. If those indicators appear, and there’s no
permission on record, Unlicensed Access has likely happened.

Some Accessing Parties might include links to the original source of results
they display. Such links would prove Unlicensed Access has happened.

Further some Accessing Parties may identify themselves using IP addresses and
User-Agent strings which can be recorded in log files to prove that access took
place.

The Contract also allows the website owner to ask the organisation involved to
explain how the content was collected and used.

Why this may come up: Enforcement against AI systems is often seen as
evidentially difficult, so this is likely to be a key practical concern.

*LEGAL NOTE*

*References to watermarks, provenance signals, data labels, and disclosure
obligations are doing heavy lifting.*

*The right to demand explanations and records is essential — do not remove or
water it down.*

*Avoid framing this as “we might ask nicely” — it is a condition of access.*

### Does the “disallow everything” language in robots.txt risk unintentionally blocking search engine access?

**Answer:** Only if it’s misconfigured, which is why alignment matters, if used
without nuance it could. The Contract and the technical signals need to say the
same thing. The intention is not to block normal search results but to clearly
block AI training and bulk data use no matter how it occurred. When those are
matched properly, search visibility is preserved.

Google do not currently list terms and conditions as a factor in search engine
results listing. If they were to modify their search index list to penalise
websites that incorporate this Contract then that could possibly be an abusive
act under antitrust laws.

*LEGAL NOTE*

*Keep language stating that technical controls operate alongside legal terms.*

*This avoids arguments that robots.txt is the only relevant signal.*

### How should publishers practically evidence repeated infringement at scale?

**Answer:** Evidence can be built by demonstrating patterns, not perfection
through keyword tracking, systematic sampling of AI outputs, and screen captures
showing replication of content. Courts and regulators don’t expect every
instance to be captured. What matters is showing that misuse is happening
repeatedly or systematically. For example, through repeated AI outputs that
closely resemble the Website Content.

*LEGAL NOTE*

*The idea of “pattern evidence” is important.*

*Avoid language suggesting every instance must be proven — that raises the bar
unnecessarily.*

### How do we address AI companies relying on third-party scrapers?

**Answer:** The Contract applies to the content wherever it ends up. If content
is passed on without permission and then used for AI, that downstream use can
still be challenged. This also highlights the need for early enforcement to
discourage liability avoidance structures.

Any AI operator found to be using unlicensed sources is likely to suffer brand
embarrassment as well as significant financial costs. This acts as a commercial
incentive to cease such practices.

*LEGAL NOTE*

*Language about “downstream use” and “derivative datasets” is legally
significant.*

*Avoid implying only the first scraper is responsible.*

### What infrastructure is needed to monitor infringement?

**Answer:** Monitoring is expected to combine mix of internal checks and
specialist tools. Publishers don’t need complex infrastructure. Simple
monitoring, combined with third party services where needed, is usually
sufficient. External services, for which there is a growing market for
third-party tools that specialise in detecting and evidencing AI-related misuse
can be used.

*LEGAL NOTE*

*Avoid language that implies surveillance obligations.*

*Emphasise proportionality.*

### Can token-based or cryptographic systems realistically track content use?

**Answer:** Yes, especially together. Tokenisation and provenance systems could
allow content to be traced across reuse contexts. No single system is perfect,
but combined technical markers make it much easier to detect content reuse and
support enforcement where problems arise.

*LEGAL NOTE*

*Keep wording that says these tools support evidence, not replace legal rights.*

### What role do data label Terms Document Locators (TDLs) and technical standards play?

**Answer:** The Data Labels standards reduce ambiguity for machines. They
provide a foundation for machine-readable permissions and traceability via
immutable URLs. Clear, machine readable links tell automated systems what
contract applies to a request. By adopting a small number of common contracts –
such as this Contract - these become machine readable in practice. This makes
compliance easier and excuses by Accessing Parties for non-compliance impossible
to justify. Standardisation and widespread adoption is key to ensuring that
these signals are recognised and respected across platforms.

*LEGAL NOTE*

*Keep “machine-readable legal restrictions” language — it connects technical
signals to legal intent.*

### Does this Contract prevent accessibility tools or assistive technologies (e.g. screen readers)?

**Answer:** No. The Contract does not restrict accessibility or assistive
technologies. Tools such as screen readers, texttospeech systems, and other
accessibility agents used to help people with disabilities access the website
are permitted. The Contract targets bulk reuse and secondary exploitation of
content, not user-facing non-commercial access (section 4.1.1).

**Why this may come up:**  
Accessibility advocates and regulators are rightly concerned about anything that
could chill or impair access for people with disabilities. This question helps
make clear that the Contract targets misuse, not accessibility.

*LEGAL NOTE  
Keep explicit language that accessibility and assistive technologies are
permitted. Avoid broad bans on “automated access” without carveouts that risks
unintended consequences. Framing accessibility tools as user-facing access
mechanisms, not secondary reuse systems, is important.*

**Can websites covered by this Contract be used for academic and research
purposes?**

**Answer:** Limited non-commercial access (including reading and research) is
permitted. However, activities such as scraping, dataset creation, or AI
training — even for research — require separate permission.

*LEGAL NOTE  
Avoid blanket exemptions for “research” or “academic use” as these can undermine
enforceability. Keep the requirement for a separate agreement clear and
explicit. Do not suggest that all academic use is prohibited; the issue is
permission, not category of user.*

### How should robots.txt and technical signals be interpreted?

**Answer:**

Technical signals such as robots.txt, HTTP headers, and other machine-readable
directives are used to communicate access permissions to automated systems.

These signals operate alongside this Contract and are intended to ensure that:

- permitted search indexing remains enabled; and
- prohibited uses such as AI training, bulk scraping, or dataset construction
  are clearly restricted.

Where these signals and this Contract are used together, they should be
interpreted consistently as part of a single access control framework.

*LEGAL NOTE:*

*This avoids the argument that robots.txt is “only technical” or “only
advisory”. You frame it as part of a unified legal-technical system, not
separate layers in conflict.*

### Do changes need to be made to HTML?

**Answer:**

No. There is no requirement to modify your website’s HTML in order to implement
the Contract.

The primary method of implementation remains through machine-readable signals
such as the robots.txt file, which identifies the applicable Terms Document
Locator (TDL).

However, publishers may choose to additionally include references to the
Contract within the HTML of their webpages. For example, where multiple licences
are used at the following URLs:

```plain
https://m4ow.uk/socw/2.txt
https://example.com/other/tos.txt
```

These can also be included in the HTML \<head\> element via the terms-of-service
link relation, as shown below:

```xml
<head>
<link rel="terms-of-service" href="https://m4ow.uk/socw/2.txt"/>
<link rel="terms-of-service" href="https://example.com/other/tos.txt"/>
</head>
```

This approach is optional and does not replace the need to correctly implement
the robots.txt configuration, but may provide an additional layer of visibility
and consistency across systems.

*LEGAL NOTE*

*Keep the distinction clear: HTML inclusion is supplementary, not required.*

*Avoid implying that HTML implementation alone is sufficient — robots.txt and
machine-readable signals remain primary.*

### Can websites covered by this Contract be used in Common Crawl?

**Answer:**

Only if Common Crawl has entered into a binding agreement ensuring that Website
Content is not used or shared for any restricted purposes under this Contract.
In practice, inclusion in Common Crawl would typically constitute Dataset
creation and downstream distribution, which is prohibited unless expressly
licensed.

### Can websites covered by this Contract be added to the Internet Archive?

**Answer:**

No, unless the Internet Archive (or equivalent service) has entered into an
express written agreement with the Website Operator permitting such activity. In
the absence of such permission, this is not a permitted use. This is because
such activity involves the systematic copying, storage, and potential
redistribution of Website Content, which falls outside the limited licence
granted under Clause 4 (Licence to Access Website) and is prohibited under
Section 7 (Prohibition on AI Scraping and Data Mining) and Section 8 (Database
Rights Protection), and is further restricted by the machine-readable controls
described in Section 10.

## COMPENSATION & COMMERCIAL USE

### How should pricing be approached given the variability in content value?

**Answer:**

There is no standard price or marketplace for valuing content. This contract
does not seek to apply a market value, the Contract simply makes clear that use
beyond search indexing is not free by default. The Contract also establishes an
Access Fee of £500 per Access Event as defined as any instance of Access to a
Product on the Website (e.g. an article, video image or photographic work,
etc.), which applies where access falls outside the permitted licensed scope.

*LEGAL NOTE*

*Preserve the statement that use requires permission first.*

*Do not suggest payment is automatic or mandatory in all cases.*

### Would introducing payment expectations undermine free search visibility?

**Answer:**

Not necessarily. The baseline model allows free use for search indexing, while
reserving other uses (such as AI training) for permission or licensing. Search
engines can continue to index content without payment. Payment only applies
where companies want to use the content for other purposes, such as AI training.

*LEGAL NOTE*

*Keep the baseline vs additional use framing.*

*Avoid wording that suggests a “paywall for search”.*

## ENFORCEMENT & LITIGATION

### What happens if a company simply ignores the Contract and operates outside the UK?

**Answer:**

Even if a company is overseas, courts can order intermediaries — like internet
providers or platforms — to stop access or block misuse. These tools are
specifically designed for situations where bad actors are hard to reach
directly.

Why this may come up: This reflects a practical enforcement concern, audiences
will want to understand whether the framework is effective against
overseas/anonymous actors.

*LEGAL NOTE*

*Terms like “website blocking orders”, “intermediaries”, and “injunctive relief”
should stay in supporting material even if not front and centre.*

*Avoid saying “we can always enforce anywhere” — stick to credible, recognised
mechanisms.*

### Is it viable to bring multiple small claims for repeated infringements?

**Answer:**

While technically possible, this is usually inefficient. Straightforward claims
may begin in lower courts for speed and cost efficiency, but complex or
high-value disputes may move to higher courts. While small claims are available,
bringing dozens or hundreds of them is inefficient. A better approach is to
group evidence and use a handful of cases to show widespread misuse. A mixed
strategy is expected, with at least one strong case used to establish precedent.
The Contract allows aggregation of multiple Unlicensed Access Events into a
single claim, and the Website Operator may choose the most efficient strategy,
including issuing aggregated claims or multiple proceedings where appropriate.

*LEGAL NOTE*

*Keep references to aggregation and representative cases.*

*This preserves flexibility without committing to one enforcement path.*

### What is the most effective litigation pathway if cases escalate?

**Answer:**

It depends on the scale and seriousness. Smaller disputes can be handled quickly
and cheaply via the UK Small Claims courts and Money Claim Online. Bigger or
more complex cases may need higher courts. Often, one strong case sets the tone
and resolves many others without further litigation.

*LEGAL NOTE*

*Avoid locking yourself into a single forum in publicfacing wording.*

*Retain discretion language such as “may” rather than “will”.*

**How do I make a claim?**

The Contract provides a structured framework for bringing claims as a debt after
issuing the invoice, including the ability to recover sums due through England
and Wales small claims track via Money Claim Online. We have prepared a "Guide
to Small Claims via Money Claims Online", which will guide you through the
practical steps such as issuing invoices, sending a Letter Before Claim, and
using the streamlined procedure envisioned by using the small claims track where
appropriate. The approach is designed to enable efficient and proportionate
enforcement, including by publishers without extensive litigation resources.
(For more detail, please see the Small Claims Guidance.) 

### Should enforcement prioritise an early test case?

**Answer:**

Yes. Establishing a clear early enforcement position helps remove uncertainty.
Once expectations are clear, many other actors adjust their behaviour without
needing further action.

*LEGAL NOTE*

*Retain emphasis on deterrence through clarity, not punishment.*

### Would a collective enforcement model be more effective?

**Answer:**

Often yes. Acting together reduces costs, avoids duplication, and increases
leverage especially against large platforms, and increases pressure on
non-compliant actors.

*LEGAL NOTE*

*Avoid wording that implies compulsory collective action.*

### Should enforcement go through regulators rather than courts?

**Answer:**

Regulatory routes complement litigation. Regulators are useful for systemic
issues, while courts remain the fastest way to stop specific misuse. However,
litigation remains an important and immediate enforcement mechanism.

*LEGAL NOTE*

*Retain litigation as an immediate option.*

### Is there a risk of retaliation from search engines or platforms?

**Answer:**

There is some risk, but large-scale withdrawal of indexing is considered
unlikely due to commercial, regulatory, and competitive pressures. Search
engines need high quality content. Widespread adoption of this Contract, or
similar policies, reduces the incentive to retaliate.

## CONTRACT ECOSYSTEM AND ADOPTION

### What is the role of a central coordinating body (e.g. Movement for an Open Web)?

**Answer:**

Primarily to coordinate policy documents, not control. Its role would be to
support standards, tools, and consistency, not to take content ownership or run
lawsuits. The model is intended to remain decentralised, with publishers
retaining full control. Publishers may wish to band together via trade bodies
for efficiency of licensing beyond the permitted uses of this Contract or for
litigation.

*LEGAL NOTE*

*Maintain decentralisation language to avoid competition or control concerns.*

### Will adoption be standardised across publishers and jurisdictions?

**Answer:**

Full standardisation is unlikely in the short term. Different markets will move
at different speeds, but shared principles are likely to emerge.
