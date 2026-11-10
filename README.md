# SACCO Loan Dashboard

Loan default risk prediction dashboard (AI course project).

- Model: Logistic Regression trained with scikit-learn on SYNTHETIC data. The trained weights are inside index.html, so it runs fully in the browser (no server).
- Not real SACCO data. Decision support only. A loan officer must review every decision.
- Demo login: admin / Admin@12345 (the login is a demo check in the page, not real security).
- Records are saved in the visitor's own browser (localStorage). Nothing is sent to a server.

## Deploy
1. GitHub: create a new repository, upload index.html, README.md, vercel.json.
2. Vercel: Add New > Project > import the repository > Deploy (no settings needed).
