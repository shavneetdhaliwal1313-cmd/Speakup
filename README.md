# SpeakUp 120 — All-Areas Human Communication Practice

This version builds the same Learn → Examples → Practise → Submit → Feedback → Reuse pattern across the practice areas.

### Vocabulary
- Meaning for every recurring vocabulary word
- Multiple natural workplace examples
- Own-sentence submission and human-focused feedback
- Additional example language after submission

### Speaking / Workplace / Client / Difficult / Writing / Networking / Negotiation / Confidence / Reading / Resources
Each area now includes an “Examples & Alternatives” toolkit showing multiple ways to communicate the same idea, plus a task that asks the learner to adapt it in their own voice.

The core standard remains: natural, clear, confident and appropriate — not robotic or AI-like.


## Navigation fix
- Fixed a duplicate JavaScript declaration that prevented the tab controller from loading.
- Added robust event-delegation navigation so sidebar and dashboard buttons reliably open the correct practice area.
- Kept each area as a separate tab/page with no large blank area above it.


## Final navigation repair
The sidebar is now controlled by an independent navigation layer. A content/rendering error cannot disable the sidebar. Each tab explicitly hides every other practice page and opens only the selected page. Dashboard navigation buttons use the same system.
