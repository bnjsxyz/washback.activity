# Washback Check

A responsive, self-contained classroom knowledge check about **positive and negative washback (backwash) in language assessment**.

## What is included

- `index.html` — the complete activity (HTML, CSS, and JavaScript in one file)
- `FACILITATOR_GUIDE.md` — objectives, suggested flow, scoring, and answer guide
- `LICENSE` — reuse terms
- `.nojekyll` — tells GitHub Pages to serve the files directly

The activity contains nine items in a fixed order for every learner: seven classification situations followed by two application challenges. All three negative-washback classification situations include a required follow-up in which the learner selects the best repair. Correct option positions vary across the activity. The maximum score is 12 points: 7 classification points, 3 repair points, and 2 application points.

Learners can move backward and forward or select any numbered item to revisit its content and submitted response. Completed items are marked in the item navigator.

## Run locally

Open `index.html` in any modern browser. No installation, account, internet connection, external font, or package is required.

## Publish with GitHub Pages

1. Create a new public GitHub repository.
2. Upload the **contents** of this folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)`, then select **Save**.
6. GitHub will display the public site address after deployment.

If an existing Pages repository is used, keep `index.html` at the selected publishing root.

## Compatibility and privacy

- Responsive layout for phones, tablets, laptops, and desktop computers
- Uses standards-based HTML/CSS/JavaScript supported by current Safari, Chrome, Edge, and Firefox
- Keyboard navigable, visible focus styles, semantic form controls, status announcements, and reduced-motion support
- No tracking and no response transmission
- Attempt progress, submitted responses, and revisited items are saved only in the learner's browser using local storage
- The results page can be printed or saved as PDF using the browser print dialog

## Academic basis

The material uses the established meaning of washback as the influence of testing on teaching and learning. Its situations operationalize constructive alignment, authentic language use, instructional narrowing, score-driven cramming, and the consequences of test content and scoring criteria.

- Alderson, J. C., & Wall, D. (1993). *Does washback exist?* Applied Linguistics, 14(2), 115–129. https://doi.org/10.1093/applin/14.2.115
- Bailey, K. M. (1996). Working for washback: A review of the washback concept in language testing. *Language Testing, 13*(3), 257–279. https://doi.org/10.1177/026553229601300303
- Messick, S. (1996). Validity and washback in language testing. *Language Testing, 13*(3), 241–256. https://doi.org/10.1177/026553229601300302

## Editing

Open `index.html` in a text editor. The question bank is in the `questions` array near the end of the file. Each negative classification item and each application item includes options and a zero-based `correct` option index. Keep the question array in the desired chronological order; the activity does not shuffle items or options.

## Suggested repository description

> A mobile-friendly interactive knowledge check on positive and negative washback in language assessment.
