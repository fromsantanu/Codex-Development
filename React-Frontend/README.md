# Using OpenAI Codex to Build React Frontends for REST APIs

Welcome! This tutorial walks backend developers through building React frontends that talk to existing REST APIs. Every step keeps things simple, uses real-life examples like customer dashboards and clinic apps, and shows how to call Codex for help.

### Part 1 – React Fundamentals
1. **Chapter 1. React basics for backend folks** – Meet JSX, components, and why React splits the UI into small building blocks; we use a simple customer list to keep it grounded.
2. **Chapter 2. Components, props, and state** – Learn how to pass data with props and keep UI state locally, with analogies such as shop counters remembering what a customer picked.

### Part 2 – React + REST APIs
1. **Chapter 3. Calling backend REST APIs from React** – Use `fetch` or `axios` to load customer and order data from `/api/customers` or `/api/orders`, and show how to keep the UI in sync.
2. **Chapter 4. Handling loading, error, and success states** – Add friendly messages and indicators so the UI feels alive while network calls run, and handle when things go wrong.
3. **Chapter 5. Building forms for creating or updating data** – Create forms that POST to `/api/patients` or PATCH `/api/customers`, with validation and simple feedback loops.
4. **Chapter 6. Simple routing and navigation** – Let users click between customer lists, detail screens, and a mini dashboard using React Router or a similar pattern.

### Part 3 – Using Codex in the workflow
1. **Chapter 7. Asking Codex to generate React components and hooks** – Learn prompts that produce list views, detail cards, and reusable hooks tied to your `/api` endpoints.
2. **Chapter 8. Using Codex for forms, API calls, refactors, and debugging** – See how Codex can add validation, extract child components, refactor fetch logic, and even troubleshoot runtime errors.

### Part 4 – Small projects to practice
1. **Chapter 9. Customer Management UI** – Build a two-panel app with a customer list, detail card, and POST form using `/api/customers`.
2. **Chapter 10. Sales Dashboard UI** – Show sales numbers from `/api/orders`, filter by region, and display trend cards while Codex helps wire up `fetch` hooks.
3. **Chapter 11. Clinic patient flow app** – Combine `/api/patients` and `/api/visits` to register patients, list upcoming visits, and navigate between screens.
