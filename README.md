## Installation

Run `npm install` command in root folder and backend folder

```
npm install
```

## How to Run

```
npm run dev
```

## How I run it

- I tried to run the backend project. For that, I created a `docker-compose.yml`, so I could run the mysql db on docker.

- It was preferred to use migration tool for the database, but I used the sql file directly.

- Some missed comma in migration file

- Missing `&` character in server command of `package.json` file

- I encountered this error for running frontend with node v19, so I had to dump the node version to v16.

```json
opensslErrorStack: [ 'error:03000086:digital envelope routines::initialization error' ],
library: 'digital envelope routines',
reason: 'unsupported',
code: 'ERR_OSSL_EVP_UNSUPPORTED'
```

- I haven't found serious issue on verification part of login and registration. It seems to be working fine. Just changed the placeholder of Email verification, for sake of user experience with browser autocomplete.
