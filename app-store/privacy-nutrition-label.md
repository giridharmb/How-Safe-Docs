# App Privacy ("nutrition label") answers for App Store Connect

**Does the app collect data?** Yes.

| Data type | Collected | Linked to user | Used for tracking | Purpose |
|---|---|---|---|---|
| Location → Coarse Location | Yes (location of a posted rating, rounded about 11 m) | No | No | App Functionality |
| User Content → Other User Content (ratings, tags, notes) | Yes | No | No | App Functionality |
| Other Data → gender, age range (optional, opt-in) | Yes | No | No | App Functionality |
| Identifiers → User ID | Yes (anonymous CloudKit record ID, used for one-vote-per-person and deletion) | No* | No | App Functionality |

\*Apple counts data as "linked" if it's tied to an account. The CloudKit user record ID is app-scoped and
pseudonymous. If App Review sees it as linked, mark **User Content** and **Identifiers** as *Linked to You*.

**Not collected:** contact info, health, financial, contacts, browsing/search history, diagnostics, purchases, usage data, sensitive info beyond the opt-in fields above.

**Tracking:** None. No App Tracking Transparency prompt is needed.
