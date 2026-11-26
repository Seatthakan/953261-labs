# 953261 Lab 2 — Kad Café (Modern JavaScript)

| | |
|---|---|
| **Name** | Seatthakan Sangkla |
| **Nickname** | Munic |
| **Student ID** | _692115043_ |
| **Section** | 701 |

## How to run

```bash
cd lab02
npm run warmup   # Part B
npm test         # Part C
npm start        # Part D — the daily report
```

## My own function (Part D)

_Name of your function, what it returns, and which array methods it uses._

itemsWithTag(menu, tag) in src/cafe.js returns an array of menu item names whose tags array includes the requested tag (for example, "spicy"), without mutating the original menu array. It uses two array methods: filter to keep matching items and map to extract their name values.

## What I learned today

_Write 2–3 sentences in your own words: when would you use map, filter, find and reduce?_

I use map when I want to transform every element into a new array of the same length, and filter when I want a subset of elements that match a condition. I use find to get the first matching item (or undefined), and reduce when I need to combine array elements into a single value like a total sum or a grouped object.

## AI-use statement

_Did you use an AI tool in this lab? If yes, which one and for what. If no, write "No AI tools used."_

Used an AI assistant during Lab 2 to explain error messages, walk through array-method logic for the exercises and daily report, and review my code while keeping full understanding of every line.
