## Backend - ArgentBank

### OpenClassrooms fork for P13 - "Développeur Concepteur Logiciel"

This codebase contains the code needed to run the backend for Argent Bank.

---

## Prerequisites

- You will need to have Node and `npm` installed locally on your machine.
- This project uses a local MongoDB database. [Download MongoDB Community Server](https://www.mongodb.com/try/download/community)

> [!WARNING]  
> The [frontend](https://github.com/Alex-Pqn/ArgentBank-ocr_dcl) must also be installed in order to launch this project.

---

## Instructions

1. Fork this repo
1. Clone the repo onto your computer
1. Open a terminal window in the cloned project
1. Run the following commands:

```bash
# Install dependencies
npm install

# Start local dev server
npm run dev:server

# Populate database with two users
npm run populate-db
```

Your server should now be running at http://locahost:3001 and you will now have two users in your MongoDB database!

### Populated Database Data

Once you run the `populate-db` script, you should have two users in your database.

| Email            | Password    |
| ---------------- | ------------|
| tony@stark.com   | password123 |
| steve@rogers.com | password456 |

---

## API Documentation

To learn more about how the API works, once you have started your local environment, you can visit: http://localhost:3001/api-docs
