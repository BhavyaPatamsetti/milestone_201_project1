# Friends API with Express and Firestore

A learning REST API for reading friends, adding a friend, changing status, and deleting records in Firestore.

## What is included

- Routes: `GET /friends`, `GET /friends/:name`, `POST /addfriend`, `PATCH /changestatus`, `DELETE /friends`.

## Getting started

Install Node.js. Create your own Firebase development project, configure `firebase.js` with private credentials, then run `npm install` and `npm start`. The server listens on port 8383. Inspect `server.js` for each request body before making mutations.

## Repository guide

- `README.md`
- `firebase.js`
- `package-lock.json`
- `package.json`
- `server.js`
- `test.rest`

## Limitations and reproducibility

The repository includes `creds.json` credential material and tracked `node_modules`. Rotate the exposed service-account key; do not use it. The test script is a placeholder. API authorization and input validation are not production-grade.
