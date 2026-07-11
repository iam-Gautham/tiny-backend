# Tiny Backend

A minimal backend server built with Node.js and Express for the FlyRank Backend Engineering assignment.

## Features

* JSON endpoint at `/`
* JSON endpoint at `/about`
* Built using Express.js

## Prerequisites

* Node.js
* npm

## Installation

```bash
npm install
```

## Run the Server

```bash
npm start
```

The server will start at:

```
http://localhost:3000
```

## API Endpoints

### GET /

Returns a welcome message.

Example response:

```json
{
  "message": "Hello, FlyRank!"
}
```

### GET /about

Returns basic information about the developer.

Example response:

```json
{
  "name": "Gautham P Sajith",
  "university": "Model Engineering College",
  "role": "Backend Engineering Intern"
}
```

## Testing

Open the following URLs in your browser:

* `http://localhost:3000/`
* `http://localhost:3000/about`

Or test using `curl`:

```bash
curl http://localhost:3000/
curl http://localhost:3000/about
```

## Tech Stack

* Node.js
* Express.js

## Author

**Gautham P Sajith**

GitHub: https://github.com/iam-Gautham
