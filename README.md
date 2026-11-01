# CareerOS — Project Index

CareerOS is the career-record and skills-intelligence product within **Become**.

## Canonical repositories

- **Frontend:** [Become-CareerOs](https://github.com/c00mbs/Become-CareerOs) — Next.js application and product interface.
- **Backend:** [careeros-api](https://github.com/c00mbs/careeros-api) — FastAPI service and authenticated career-data API.
- **Historical backend:** [careeros-api-authenticated](https://github.com/c00mbs/careeros-api-authenticated) — superseded implementation retained for reference. Do not deploy or describe it as the active backend.

## Current implementation status

The active frontend repository documents registration, sign-in, authenticated dashboard reads, skill creation, timeline and opportunity workflows. The backend repository documents Argon2 password hashing, short-lived JWT bearer tokens, user-scoped endpoints, resume upload handling, and a 9-test automated suite.

The repository documentation reports a successful frontend production build and passing backend tests. These are documented CI claims, not an independent production acceptance test.

**Not yet verified in this index review:** live Render health, production CORS configuration, successful browser sign-up/sign-in against the deployed API, persistence across sessions, and the complete user journey.

The frontend README also identifies remaining product work, including production hardening of token handling, profile editing, experience/education CRUD, and full application-tracker creation.

## Honest portfolio description

CareerOS is an in-development career-management product with a Next.js frontend and FastAPI backend. The repositories contain implemented application and authentication flows; live production integration and end-to-end behavior must be verified before describing the platform as production-ready.

## Deployment references

- Backend service: [careeros-api-yadv.onrender.com](https://careeros-api-yadv.onrender.com)
- Frontend deployment: Not yet confirmed in the Vercel account review.
