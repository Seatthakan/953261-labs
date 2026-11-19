# 953261 Lab 1 — First Node.js Server

| | |
|---|---|
| **Name** | Seatthakan Sangkla |
| **Nickname** | Munic |
| **Student ID** | 692115043 |
| **Section** | 701 |

## How to run

```bash
cd lab01
npm start
```

Then open <http://localhost:3000> and <http://localhost:3000/api/me>.

## What I learned today

_Write 2–3 sentences in your own words: what happens between typing a URL and seeing the page?_

When I type a URL in the browser, it sends a request to my Node.js server on `localhost:3000` and prints the method and path in the terminal. The server checks the path and sends back HTML (`200`), JSON for `/api/me`, or `404` for other paths. Then the browser shows the result on the screen.

## AI-use statement

_Did you use an AI tool in this lab? If yes, which one and for what (e.g., "ChatGPT to explain a Git error message"). If no, write "No AI tools used."_

Yes, I used Gemini to help me understand the lab steps, fix terminal and Git errors, and check my code, and I wrote/checked it myself.
