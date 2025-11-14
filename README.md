# Request Info

Visiting the project's root will neatly display all the request headers.

Since the project is responsive, it will also work on phones.

## Setup

Download the files and then run `npm install`.

Create a `.env` file containing `PROJECT_NAME` and `PROJECT_PORT` before using. Here's a sample configuration:

```
PROJECT_PORT=3000
PROJECT_NAME="Request Info"
```

## Scripts

- `npm run dev`: will show errors inside the browser, will not cache EJS files, ecc
- `npm run production`: will set NODE_ENV to "production".