# CareFlow — Hospital Patient Management System

A responsive, browser-based educational prototype based on the supplied abstract.

## Run it
1. Open `index.html` in a modern browser.
2. Use **Register patient** to add demo patients.
3. Normal patients are processed FIFO (arrival order).
4. Emergency patients are ordered by demonstration priority (Level 1 is highest); ties follow arrival order.
5. **Call next patient** chooses the highest-priority waiting emergency first, then the earliest normal patient.
6. Patient data persists in the same browser via `localStorage`.

## Included
- Dashboard with waiting counts and recent activity
- Add patient form: ID, name, age, medical problem, category, emergency priority, notes
- Searchable patient list, status filters, detail view, call and remove actions
- Separate emergency priority queue and normal FIFO queue
- Responsive layout for desktop and mobile
- Data stored locally in browser

## Important
This is a front-end educational demo, not a production hospital information system. It has no server, database, authentication, encryption, audit controls, or multi-user synchronization. Do not enter real patient-identifiable or confidential health data. The priority levels are illustrative and do not replace clinical triage or emergency procedures.
