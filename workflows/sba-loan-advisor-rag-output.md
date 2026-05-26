# SBA Loan Advisor (RAG) — Sample Output

Workflow: Manual Trigger → Set Question → Search Splicewire → Format Context → Ask OpenAI

## Question

> What are the eligibility requirements for an SBA 7(a) loan?

## Sources Retrieved

5 regulatory fragments retrieved from Splicewire hybrid search (BM25 + pgvector RRF), scoped to `SBA Lending`.

| # | Source | Score |
|---|--------|-------|
| 1 | https://www.sba.gov/partners/lenders/7a-loan-program/terms-conditions-eligibilit | 0.0325 |
| 2 | https://www.sba.gov/funding-programs/loans/7a-loans | 0.0318 |
| 3 | 13 CFR § 120.341 — Who is eligible? | 0.0310 |
| 4 | 13 CFR § 120.100 — What are the basic eligibility requirements for all applicant | 0.0164 |
| 5 | 13 CFR § 120.398 — America's Recovery Capital (ARC) Loan Program. | 0.0159 |

## Answer

The eligibility requirements for an SBA 7(a) loan are outlined in the regulatory context and include the following criteria:

1. The business must be an operating business.
2. The business must operate for profit.
3. The business must be located in the United States.
4. The business must be classified as small under SBA size requirements (refer to 13 CFR Part 121).
5. The business must not fall under the category of ineligible businesses as specified in 13 CFR § 120.110.
6. The business must demonstrate that it cannot obtain the desired credit on reasonable terms from non-federal, non-state, and non-local government sources.
7. The business must be creditworthy and show a reasonable ability to repay the loan.

Additionally, per 13 CFR § 120.341, an applicant must be in business for one full year at the time of application, although this requirement may be waived if the applicant has sufficient export trade experience or other managerial experience.

---
*Model: gpt-4o-mini-2024-07-18 | Tokens: 1804 prompt + 198 completion = 2002 total*
