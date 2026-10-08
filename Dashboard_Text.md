# Overview

Customer snapshot: 30 September 2026. Payments: April-September. CRM: export status including October closes.

Data confidence: Moderate

Analyst judgment, not a statistical score. Missing CRM-payment links and historical activity; inconsistent attribution; CRM dates beyond September. 35 calculation checks passed.

Estimated ledger proceeds

₹38,80,135

Includes QA payments. Customer-only: ₹37,53,583. Bank settlements unavailable.

Active customer MRR

₹11,50,845

Pro ₹5,39,892; Elite ₹6,10,953. QA/churn excluded.

Webinar CRM wins

15 / 415

15 export-status wins; 11 closed by September 30. No captured payment matches the 15 wins.

Webinar funnel
Registered
415
100%
Attended
220
53%
Sales pipeline
59
14.2%
CRM won
15
3.6%

401 distinct people across 415 person-webinar registrations.

Payment-cohort proceeds
Apr 1
May 1
Jun 1
Jul 1
Aug 1
Sep 1
₹0
₹250K
₹500K
₹920.1K
Full ledger
Customer only

Refunds assigned original payment month. Not bank cash flow.

Spend per active paid signup
₹0
₹30K
₹60K
₹87K
Google
LinkedIn
Meta

July-September. Descriptive cost, not causal CAC. Meta: controlled-test recommendation.

Signup cohort snapshot
Apr 2026
May 2026
Jun 2026
Jul 2026
Aug 2026
Sep 2026
0%
25%
50%
75%
100%
Active status
September usage

Historical retention unavailable. September is activation; cohort ages differ.

# Webinars

Per-webinar conversion
Counts and stage conversion
Counts and stage conversion
Webinar	Registered	Attended	Pipeline	Won	Reg-attend	Attend-sales	Sales-won	Reg-won
How to Crack Senior Roles in 2026	147	82	27	5	55.78%	32.93%	18.52%	3.40%
Negotiating a 40% Salary Jump	141	67	13	4	47.52%	19.40%	30.77%	2.84%
Resume Teardown: Live with Hiring Managers	127	71	19	6	55.91%	26.76%	31.58%	4.72%

Only 11/15 wins closed by 30 September. Open deals and unequal follow-up windows limit comparisons.

Sources and engagement
Registration-to-win by source
0%
2.5%
5%
6.1%
Google
Referral
LinkedIn
Meta
Direct
Organic

Google has the highest observed conversion, but the sample does not establish statistical superiority. Broad platform groups; overlapping confidence intervals.

Win rate by session duration
0%
4%
8%
11%
Not attended
0-14 min
15-29 min
30-44 min
45+ min

Higher engagement is directionally associated with better conversion, but the sample is insufficient to establish causality. 45+ min: 9/82; shorter: 6/138; Fisher p=0.094.

# Revenue and cohorts

Revenue and plans
Estimated proceeds by payment month
Estimated proceeds by payment month
Month	Ledger net	Customer net
2026-04	₹1,85,487	₹1,65,963
2026-05	₹4,44,397	₹4,29,872
2026-06	₹6,47,823	₹6,23,418
2026-07	₹8,90,871	₹8,61,702
2026-08	₹9,20,098	₹9,05,573
2026-09	₹7,91,461	₹7,67,056
Active customer MRR
Active customer MRR
Plan	Active users	MRR
Elite	47	₹6,10,953
Free	147	₹0
Pro	108	₹5,39,892

Full-refund and fee-exclusive assumptions. Fee-inclusive ledger alternative: INR 3,895,744.84.

Cohort evidence
September snapshot by signup cohort
September snapshot by signup cohort
Signup month	Signups	Active status	Status %	September usage	Usage %
2026-04	187	42	22.46%	0	0.00%
2026-05	188	53	28.19%	20	10.64%
2026-06	209	48	22.97%	73	34.93%
2026-07	210	53	25.24%	143	68.10%
2026-08	215	55	25.58%	189	87.91%
2026-09	191	51	26.70%	191	100.00%

Retention analysis unavailable with the current export. April: 42/187 active labels, zero September last-active records. Collect customer ID, timestamp and a defined qualifying activity for monthly events, plus subscription history.

Channel comparison
July-September customer economics
July-September customer economics
Channel	Signups	Currently paid	Spend	Spend / paid signup	Cohort MRR
Google	159	19	₹13,05,792	₹68,726	₹1,26,981
LinkedIn	79	11	₹9,57,069	₹87,006	₹78,989
Meta	191	26	₹13,02,204	₹50,085	₹1,93,974
Organic	125	16	Not supplied	Not supplied	₹1,35,984
Referral	62	8	Not supplied	Not supplied	₹55,992

Meta: measured incremental test. Organic/Referral costs are missing, not zero.

# Data quality

Data-quality register
Severity
All
Observed problems and treatment
Data-quality issues
Dataset	Issue	Count	Severity	Treatment
zoom_webinar_registrants	Exact duplicate rows	4	Medium	Remove exact duplicates
zoom	Emails need case/whitespace normalization	237	Medium	Trim and lowercase; never remove dots or plus tags
sales_pipeline	Exact duplicate rows	3	Medium	Remove exact duplicates
sales	Emails need case/whitespace normalization	35	Medium	Trim and lowercase; never remove dots or plus tags
zoom	Repeat registrations for same person and webinar	8	Medium	One person-webinar; earliest registration/source, any attendance, maximum valid duration
zoom	Conflicting attendance within repeat registrations	4	Medium	Use any Yes; retain exceptions
zoom	Different durations for repeat registrations	1	Medium	Use maximum, not sum; sensitivity separately
zoom	Source-label spellings	30	Medium	Use documented alias mapping; no paid/organic separation
1–8 of 40 results
Page 1 of 5

35 automated checks passed. Issue counts may overlap. Published evidence contains aggregates only.

# Decisions

What should NxtJob do next?
P0 - Fix attribution

Connect webinar registration, CRM opportunity, payment and product activity with one customer identity. Reconcile payment IDs with settlements before scaling acquisition.

P1 - Run a controlled Meta test

Increase spend modestly; compare 30-day payments and activity against a holdout. Current spend per active paid signup is not incremental ROAS or causal CAC.

P1 - Improve webinar follow-up

Segment by engagement and randomize higher-touch follow-up within comparable groups. Test Resume Teardown characteristics with equal outcome windows, rather than simply increasing webinar volume.

Volume leakage versus rate weakness
Records not progressing to the next stage
Records not progressing to the next stage
Step	Entered	Progressed	Not progressed	Drop-off
Registration -> Attendance	415	220	195	46.99%
Attendance -> Pipeline	220	59	161	73.18%
Pipeline -> Won	59	15	44	74.58%

Registration-to-attendance loses the most records. Pipeline-to-won has the highest proportional drop, slightly above attendance-to-pipeline. Open deals are not necessarily permanent losses.

Observed, interpretation, action
Source comparison

Observed: Google registered-to-won conversion is 6.06%.

Interpretation: Google looks stronger in these webinar cohorts, but the sample does not establish statistical superiority.

Action: retain Google in the webinar mix while testing incremental Meta spend. Compare reconciled outcomes on the same customer and observation window.

90-day measurement roadmap
Now - Days 1-30

Fix identity; confirm payment test/live mode, refund amount/time and settlement IDs/dates. Agree KPI definitions and reconcile complete journeys.

Next - Days 31-60

Instrument monthly product events, subscription history and CRM stage changes. Carry campaign IDs through signup/payment and use consistent follow-up windows.

Then - Days 61-90

Build reconciled acquisition costs and cohort retention; evaluate holdout tests. Add LTV only with sufficient history and an explicit margin model. Timing is proposed.

# KPI definitions

KPI definitions
Counting rules, populations and periods
Counting rules, populations and periods
Metric	Definition	Period
Registered	Unique trimmed/lowercase email per webinar after exact deduplication and repeat consolidation. A person can count once in each webinar.	Webinar cohorts in supplied export
Attended	Registered person-webinar with any Yes attendance across repeat rows. Maximum duration is used, not sum.	Webinar cohorts in supplied export
Pipeline lead	Registered person-webinar matched to CRM on email and exact first_touch webinar, with lead creation on/after registration and webinar day.	Supplied CRM export; all matched leads attended
Won	Matched pipeline record with CRM export status won. Separate September-cutoff count requires a close date on/before September 30; no historical status reconstruction.	15 export-status wins; 11 closed by September 30
Active customer	Non-QA user with supplied account status active. This is a lifecycle label, not proof of product usage.	September 30 user snapshot
Active paid signup	Non-QA user signed up July 1-September 30, currently active, on Pro/Elite with positive supplied MRR. Not necessarily a newly captured payer.	July-September cohorts; September 30 status
MRR	Sum supplied mrr_inr for active, non-QA Pro/Elite users with positive MRR. Excludes churned and Free; not cash receipts.	September 30 snapshot
Net proceeds	Captured + refunded principal minus assumed full refunds, processing fees and fee tax. Failed attempts zero. Fees assumed pre-tax; inclusive sensitivity shown. Ledger includes QA-linked payments; customer-only excludes them.	April-September payment-created dates, not settlement dates
1–8 of 11 results
Page 1 of 2

# KPI definitions (continued)

KPI definitions
Counting rules, populations and periods
Counting rules, populations and periods
Metric	Definition	Period
Spend per active paid signup	July-September platform spend / currently active paid signups from the same signup window and user acquisition channel. Descriptive ratio, not causal CAC. Organic/Referral costs unavailable.	July-September spend and signup cohorts
CAC	Not established. Requires agreed acquisition-cost scope and reconciled new-customer payment/identity attribution. Spend per active paid signup must not be relabelled CAC.	Unavailable with current exports
September cohort activity	Non-QA users with last_active_at in September / all non-QA signups in each cohort. Earlier monthly activity unknown; September cohort is same-month activation.	September activity by signup month
9–11 of 11 results
Page 2 of 2

# Data quality (page 2)

Data-quality register
Severity
All
Observed problems and treatment
Data-quality issues
Dataset	Issue	Count	Severity	Treatment
zoom	Paid versus organic platform source ambiguous	325	High	Report broad platform only
zoom	Missing city	59	Medium	Keep missing; not needed for core calculations
sales	Missing deal amounts	40	Medium	Do not infer missing values from plan
sales	Won deals missing value	2	Medium	Exclude missing from value totals; wins counted
sales	Non-open deals missing close date	9	High	Include export status; flag as-of outcome unknown
sales	Close dates after product snapshot	8	High	Export funnel separate from Sep30 as-of sensitivity
sales	Close dates after review date	3	High	Use supplied status, not a live operational claim
sales	Elite deal value equals Pro amount	2	Medium	Flag; retain, do not assume incorrect
9–16 of 40 results
Page 2 of 5

35 automated checks passed. Issue counts may overlap. Published evidence contains aggregates only.

# Data quality (page 3)

Data-quality register
Severity
All
Observed problems and treatment
Data-quality issues
Dataset	Issue	Count	Severity	Treatment
razorpay_transactions	Exact duplicate rows	5	Medium	Remove exact duplicates
payments	Emails need case/whitespace normalization	394	Medium	Trim and lowercase; never remove dots or plus tags
payments	Mixed Unix-second and naive timestamp formats	285	Medium	Epoch UTC; naive interpreted UTC for primary; IST sensitivity included
payments	No timezone for naive timestamps	434	High	Document UTC alignment assumption
payments	Multiple attempts for same order	127	Medium	Deduplicate payment ID, preserve order attempts
payments	No refund amount/date or settlement fields	N/A	Critical	Full refund assumption; estimated proceeds not verified bank cash
payments	Fee tax semantics conflict with native API	N/A	High	Primary: fee exclusive per dictionary and 2% pattern; show fee-inclusive sensitivity
users_db	Exact duplicate rows	6	Medium	Remove exact duplicates
17–24 of 40 results
Page 3 of 5

35 automated checks passed. Issue counts may overlap. Published evidence contains aggregates only.

# Data quality (page 4)

Data-quality register
Severity
All
Observed problems and treatment
Data-quality issues
Dataset	Issue	Count	Severity	Treatment
users	Last activity predates signup timestamp	4	Medium	Date-grain cohorts; flag before claiming precise lifecycle
users	Last activity predates signup date	1	High	Retain for counts; quarantine activity inference if nonzero
users	Churned users carry positive MRR	36	High	Exclude from active MRR
users	Free users carry positive MRR	4	High	Exclude from primary MRR; sensitivity as unresolved active MRR
users	Active paid-plan users have zero MRR	5	High	Keep supplied zero; do not infer tariff
users	Missing city	198	Medium	Keep unknown
users	No historical activity or plan changes	N/A	High	Show September activity by signup cohort; historical cells N/A
users	Status and activity may disagree	614	Medium	Show both measures; do not relabel one as the other
25–32 of 40 results
Page 4 of 5

35 automated checks passed. Issue counts may overlap. Published evidence contains aggregates only.

# Data quality (page 5)

Data-quality register
Severity
All
Observed problems and treatment
Data-quality issues
Dataset	Issue	Count	Severity	Treatment
users	Last-active timestamp concentrated at Sep30 midnight	430	Medium	Use month-grain activity proxy with caveat
users	Explicit QA test accounts	18	High	Exclude all 18 jointly identified QA Test / usr_T accounts from customer metrics
payments	Transactions linked to explicit QA accounts	32	High	Keep full ledger proceeds and disclose customer-only sensitivity; exclude from channel/customer economics
cross-source	Webinar registrants absent from users	194	Medium	Keep webinar funnel standalone
cross-source	Webinar CRM wins without captured payer match	15	High	Do not equate won deal value to payments
cross-source	Webinar source differs from user acquisition channel	6	Medium	Keep registration-source and user-channel analyses separate
cross-source	Ad spend covers less history than signups/payments	N/A	High	Use July-Sep comparisons only; no all-period ROAS
cross-source	No campaign IDs or purchase attribution	N/A	High	Use platform-level descriptive ratios only
33–40 of 40 results
Page 5 of 5

35 automated checks passed. Issue counts may overlap. Published evidence contains aggregates only.