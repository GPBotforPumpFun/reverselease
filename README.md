# ReverseLease prototype

Buyer-led reverse lease marketplace concept. Node 22+, no dependencies. Run `npm start`, open port 3000. Railway uses PORT and /health.

Interactive buyer requests, dealer offers, cost ranking, comparison table, shortlisting, and simulated worksheet requests. All records live in localStorage per browser, seeded with explicitly illustrative data. Reset demo restores the seed. No accounts, shared backend, real dealers, notifications, credit checks, or binding transactions. Do not enter sensitive information.

Total scheduled cost = cash due + monthly payment * (term minus 1 if first payment is included at signing). Effective monthly = scheduled cost / term. Disposition is disclosed separately. Quotes disclose fees but are not independently verified or calculated from lender programs. Different terms and mileage are flagged. Production requires dealer verification, authenticated roles, durable shared storage, audit trail, inventory and quote validation, and consent-based communication.
