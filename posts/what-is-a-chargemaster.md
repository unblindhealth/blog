Almost every number on a hospital bill traces back to one internal document: the **chargemaster**, formally the charge description master, or CDM. It's a database of list prices — tens of thousands of rows, covering everything from a complex surgery to a single dose of medication to a box of gauze.

It's also, in practice, the most misread document in American healthcare, because it looks like a price list and functions like an opening bid.

## What's actually in it

Each row maps one billable item to a **gross charge** — the list price. A typical entry has:

- An internal item number
- A CPT or HCPCS code
- A short description, usually cryptic and incomplete
- The gross charge

That's it. What it does *not* contain is what anything costs to deliver, or what anyone actually pays.

## Why the prices look absurd

Because they are — and there's published research quantifying it.

Researchers at Johns Hopkins examined hospital **charge-to-cost ratios**: how much a hospital charges relative to its costs. In 2013, the average hospital with more than 50 beds charged about **$4.32 for every $1 of cost**. By 2017, the median ratio was around 3.5, with hospitals at the 90th percentile at 6.6 ([Health Affairs study](https://www.healthaffairs.org/doi/abs/10.1377/hlthaff.2016.0093) / [Johns Hopkins summary](https://hub.jhu.edu/2016/09/08/hospital-markups-price-gouging)). A separate 2022 study confirmed prices remain significantly inflated: discounted cash prices averaged 60% higher, and chargemaster list prices averaged 164% higher, than negotiated insurance rates across common procedures ([Medical College of Wisconsin study](https://pmc.ncbi.nlm.nih.gov/articles/PMC9464687/)).

The disparity gets more pronounced at the department level. Ratios ranged from **1.8 for inpatient general routine care to 28.5 for CT scans**, with anesthesiology close behind at 23.5. In the researchers' own illustration: a hospital whose CT department costs are $100 will charge **$2,850** to an uninsured patient or an out-of-network privately insured one.

The markup isn't uniform across a hospital — it's concentrated in specific services. As the study's lead author put it, hospitals "mark up higher in the departments with more complex services because it is more difficult for patients to compare prices in these departments." If you've wondered why imaging bills look disconnected from reality, that's the answer — and it's a fairly direct statement of the problem this site is trying to solve.

Ratios also varied by ownership and market power:

| Hospital type | Average charge-to-cost ratio |
|---|---|
| Government-run | 3.47 |
| Nonprofit | 3.79 |
| For-profit | 6.31 |
| System-affiliated | 4.76 |
| Independent | 3.54 |
| With regional market power | 4.56 |
| Without regional market power | 4.16 |

*(Figures above are from Bai & Anderson, 2016, using 2013 data — the most rigorous published work on this.)*

### Three explanations — and one of them is disputed

1. **Historical inertia.** Prices get marked up from an old base, year over year, with no particular relationship to cost. Nobody rebuilds the list from scratch; it just accumulates.
2. **Negotiating leverage.** A high list price is a starting position for insurer negotiations, and it sets the ceiling for anyone without a negotiated rate. The Johns Hopkins researchers concluded markups are used to maximize revenue — a finding, not an accusation.
3. **Cost shifting — the disputed one.** The industry argument is that private prices are raised to cover shortfalls from Medicare and Medicaid. It's repeated so often it reads as fact, but health economists have largely disputed it: research has found that a 10% reduction in Medicare payments was associated with roughly an **8% reduction** in private prices — the opposite of what cost-shifting predicts ([Center for Public Integrity](https://publicintegrity.org/health/the-enduring-myth-of-cost-shifting/); [Paragon Health Institute](https://paragoninstitute.org/paragon-prognosis/busting-the-myth-of-hospital-cost-shift/); [University of Texas Medical Branch review](https://pubmed.ncbi.nlm.nih.gov/18972987/)).

The more common economic explanation is market power: hospitals with less local competition charge more because they can, not because they must. Some researchers argue both effects operate, depending on hospital governance and market conditions.

## Who actually pays chargemaster prices?

Almost nobody, in full — but the exposure isn't evenly distributed.

| If you are… | What you pay |
|---|---|
| Insured | Your plan's negotiated rate, typically far below list |
| On Medicare or Medicaid | Fixed, regulated federal and state amounts unrelated to the list price |
| Uninsured or paying cash | The most exposed — but you can ask for the **cash price**, a distinct, lower published rate |

That last row is the practical reason UnblindHealth exists. If you're paying without insurance, the gross charge is not your price unless you accept it as your price. Ask for the cash price by name. Always.

## What changed in 2021, and what changed again in 2026

Since **January 1, 2021**, U.S. hospitals have been required to publish their standard charges — gross charges, cash prices, and payer-specific negotiated rates — in machine-readable files.

Since **April 1, 2026**, [CMS](https://www.cms.gov/priorities/key-initiatives/hospital-price-transparency) has enforced tighter requirements from the [CY2026 OPPS final rule](https://www.cms.gov/newsroom/fact-sheets/cy-2026-opps-ambulatory-surgical-center-final-rule-hospital-price-transparency-policy-changes): hospitals must publish **actual dollar amounts** rather than estimates, including median allowed amounts and 10th/90th percentile figures.

That second change matters more than it sounds. Estimates were vague, and inconsistent formats made comparison nearly impossible. Actual dollar amounts can be compared directly — including against the allowed amount on your own EOB.

## The part nobody says out loud

The data being public hasn't meant the data being used.

[NPR reported](https://www.npr.org/2026/02/10/nx-s1-5704792/health-care-price-transparency-data) in February 2026 that despite the rules, the published price files are sparse and confusing enough that it's mostly health systems and insurers using them to negotiate with each other — not patients shopping for care.

That gap is what motivated this site. The transparency requirement exists, but the average person has no practical way to find or interpret it — the data is being used by hospitals and insurers to negotiate among themselves, when the intent was to make it usable by the person actually paying the bill. A legal right to information you can't practically read is a strange kind of right. We read the files so the answer is waiting for you before you're asked to pay.

## What to actually do with this

- **Never treat the gross charge as your price.** It's the number the chargemaster produced, not the number you owe.
- **If you're paying cash, ask for the cash price by name.** It's a separate, published amount.
- **[Look up the published price](https://unblindhealth.com/procedures) before a scheduled procedure.** Non-emergency care is where this knowledge is worth the most, because you can still choose where to go.
- **When a bill arrives, compare it to the hospital's own published file.** "This seems high" is easy to deflect. "Your published price is lower, and here it is" is a different conversation — see [how to read your bill](https://unblindhealth.com/blog/how-to-read-a-hospital-bill).
- **Watch the high-markup departments.** Imaging and anesthesia carry some of the steepest ratios — they're the lines most worth checking.

## FAQ

**What is a hospital chargemaster?**
An internal database listing a hospital's gross charge for every billable service, supply, and procedure — often tens of thousands of entries. It's the starting point for most figures on a bill, and it's a ceiling, not a final number.

**Does anyone pay chargemaster prices?**
Rarely in full. Insurers pay negotiated rates, Medicare and Medicaid pay regulated amounts, and uninsured patients can request the cash price. Those without coverage who don't ask are the most exposed.

**Why are chargemaster prices so high?**
Published research puts average charge-to-cost ratios around 3.5–4.3x, and far higher in some departments. The main drivers are historical markup practices and negotiating leverage. "Cost shifting" is commonly cited but disputed by health economists.

**Are hospital prices public?**
Yes. Since 2021, hospitals must publish standard charges in machine-readable files, and since April 2026, those files must contain actual dollar amounts rather than estimates. The files are public but difficult to read without tooling.

**What's the difference between the gross charge and the cash price?**
The gross charge is the list price from the chargemaster. The cash price is a separate, lower published price for patients paying without insurance.

> ⚠️ **This is price information, not medical, legal, or insurance advice.** Prices, policies, and regulations vary by hospital and change over time — confirm directly with the facility, and check your own plan documents. Don't delay care you need over a pricing question.

*Sources: Ge Bai & Gerard F. Anderson, ["US Hospitals Are Still Using Chargemaster Markups To Maximize Revenues,"](https://www.healthaffairs.org/doi/abs/10.1377/hlthaff.2016.0093) Health Affairs, September 2016 — all charge-to-cost ratios cited here come from that study, based on 2013 financial data from Medicare-certified U.S. hospitals with more than 50 beds ([Johns Hopkins summary](https://hub.jhu.edu/2016/09/08/hospital-markups-price-gouging)) · [CMS Hospital Price Transparency rule](https://www.cms.gov/priorities/key-initiatives/hospital-price-transparency) and [CY2026 OPPS final rule](https://www.cms.gov/newsroom/fact-sheets/cy-2026-opps-ambulatory-surgical-center-final-rule-hospital-price-transparency-policy-changes) · [NPR, February 2026](https://www.npr.org/2026/02/10/nx-s1-5704792/health-care-price-transparency-data) · cost-shifting literature per [Center for Public Integrity](https://publicintegrity.org/health/the-enduring-myth-of-cost-shifting/), [Paragon Health Institute](https://paragoninstitute.org/paragon-prognosis/busting-the-myth-of-hospital-cost-shift/), and [peer-reviewed review](https://pubmed.ncbi.nlm.nih.gov/18972987/). Checked July 2026. Where a widely repeated industry claim is contested in the research, this post says so rather than restating it as fact.*
