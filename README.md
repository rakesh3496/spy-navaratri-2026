# SPY Navaratri 2026 - Updated App

Updated features:
- Centralized Firebase Firestore data
- Shared committee password + unique usernames
- Dashboard metrics: collections, expenses, balance, contributors, transactions, average collection, pending expenses
- Complete PDF financial report
- Date-range filtering for PDF
- All collection and expense transactions with date, amount, payment mode/status, username and details
- Committee member summary
- Existing calendar and feedback features
- PWA support

Firebase Authentication: Anonymous sign-in must be enabled.
Firestore rules: see firestore.rules.

Committee password: spy@2026
Admin password: spy@202627

This is intentionally lightweight for the temporary committee use case. The committee password is a client-side gate; it is not strong security.
