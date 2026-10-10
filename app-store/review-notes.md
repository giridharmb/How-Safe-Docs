# Notes for App Review

- The app needs no login. Browsing works without iCloud; posting a rating needs an iCloud account on the device.
- **User-generated content safeguards (Guideline 1.2):** users accept the community guidelines during onboarding; every note can be reported (⋯ → Report this note); notes reported by 3 or more people are hidden automatically; the client filters phone numbers, links, addresses, emails and slurs; moderators can remove content from the CloudKit Console; contact information is on the support page.
- Location is used only "While Using", to centre the map and find nearby safe places.
- The SOS tab starts a `tel:` call only after a confirmation dialog.
- **Background location (v1.1):** used only when the person turns on *Area alerts* (CLMonitor geofences around low-rated areas) or during an active *Walk with me* session (to include the latest location in a check-in message they choose to send). Location is never uploaded.
- **Time-sensitive notifications:** used only for Walk with me check-in deadlines.
- **Messages:** the app never sends SMS itself; it presents MFMessageComposeViewController for the user to send.
- To test Walk with me quickly: Safety → Walk with me → add a contact → choose 5 min (stepper) → Start.
