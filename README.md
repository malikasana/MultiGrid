# MultiGrid

**A visual multiplication tool that breaks any number into place-value steps — every cell is just a times-table fact.**

🌐 **Live Site:** https://multigrid-d104.onrender.com

---

## What is this?

MultiGrid is an interactive web-based multiplication worksheet. It takes any two numbers (X up to 4 digits, Y up to 2 digits) and walks through the full multiplication process visually — the same way you'd do it on paper, but digitally.

Instead of doing `9999 × 99` in one shot, MultiGrid breaks it into small pieces:
- Split X by place value → **K** (thousands), **H** (hundreds), **T** (tens), **U** (units)
- Multiply each piece by each digit of Y
- Assemble the partial results by place value
- Add the row totals to get the final answer

If you know your 1–10 times tables, you already know how to multiply any two numbers.

---

## Files

| File | Purpose |
|------|---------|
| `index.html` | The live interactive web tool — enter any numbers and it fills the grid automatically |
| `MG_FINAL.pdf` | A completed example showing `9999 × 99` worked out by hand — use this to understand how the grid works |
| `MG_FINAL_USABLE.pdf` | A blank practice sheet — print it out and fill it in yourself |

---

## How the Grid Works

### Step 1 — Multiplication Grid
X is broken into its place-value digits. Each cell in the grid shows one digit position of the product of an X-piece and a Y-piece. Add each column downward to get the SUM row.

### Step 2 — Assemble by Place Value
Each SUM is copied into the assembler table, placed at its correct place-value column. Add across each row to get the Row Total.

### Final Answer
Add all Row Totals together. That's your answer.

---

## Purpose

This tool was built to make long multiplication visual and approachable. It's designed for:
- Students learning place-value multiplication
- Teachers who want a structured worksheet format
- Anyone who wants to see exactly why long multiplication works

---

## Tech

Plain HTML, CSS, and JavaScript — no frameworks, no dependencies beyond a Google Font. Opens in any browser.

---

## License

Free to use for educational purposes.
