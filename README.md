# Commission Work Programme Delivery Elements

## One-sentence benefit
Helps policy teams turn the 2027 Commission work programme into accountable initiatives and milestones.

## Live demo
Run both layers locally, then follow [the verified application demo](docs/demo.webm).

## Screenshots
![Commission work programme delivery workspace](docs/screenshot.png)

## Main features
Search and sort delivery files, create a simplification item, advance milestones and inspect priority gaps.

## Technology used
Lit, TypeScript, native Web Components, Vite, Spring Boot and Java.

## Installation instructions
Start `cd backend && mvn spring-boot:run`, then run `npm install && npm run dev` in another terminal.

## Commercial licensing/contact
Commercial licensing and implementation support are available through the repository owner.

## Business problem and users
Policy units, secretariats and public-affairs teams need one view of initiatives, proposals, owners and delivery evidence.

## Key workflows
Filter delivery files, create a Benelux simplification item and move a real backend record through review.

## Lit and Web Components highlights
A typed custom element, reactive state, keyed repeat rendering, a controller and reusable status cards are demonstrated.

## Java backend highlights
Spring Boot provides real list, search, create and update endpoints, validation, clear errors, health reporting and tests.

## Architecture and state flow
The custom element fetches authoritative Java records and re-renders when reactive state changes.

## Accessibility and responsive behaviour
Semantic headings, labelled search, visible status text, strong contrast and responsive layouts support varied devices.

## Verification commands
Use `npm test`, `npm run build`, and `cd backend && mvn test package`.

## Structure
`src` contains Lit components, `backend` contains Java, and `docs` contains verified media.

## Tradeoffs
The in-memory store keeps setup simple; production would add identity, legislative dependencies and durable evidence.

## Roadmap
Add annex imports, interinstitutional milestones, multilingual briefs, dependency maps and deadline alerts.
