# IRC Technical Screener: Application Task

Thank you for your interest in the role at the International Rescue Committee.

In place of a cover letter, please complete this short data task. It should take less time than writing a traditional cover letter.

## Files

Download both files from this repository:

**donors.csv**: one row per donor

| Column | Description |
|---|---|
| donor_id | Unique donor identifier |
| segment | Donor segment: Standard Value, Mid-Level or High Value |
| country | Donor country: US or UK |

**gifts.csv**: one row per gift

| Column | Description |
|---|---|
| gift_id | Unique gift identifier |
| donor_id | Donor who made the gift (links to donors.csv) |
| gift_date | Date of the gift (YYYY-MM-DD) |
| amount_usd | Gift amount in US dollars |
| channel | Channel the gift came through |
| status | Completed or Refunded |

The data is synthetic and does not relate to real donors.

## Instructions

Use any tool you like (SQL, Python, R or similar).

- Use only gifts with status **Completed**.
- Years are calendar years, based on gift_date.

## Questions

**Q1.** What was the total value of completed gifts from High Value donors in 2025, to the nearest dollar?

- A) $474,392
- B) $587,690
- C) $404,515
- D) $992,206
- E) $477,451

**Q2.** Among Mid-Level donors in 2025, which channel had the highest average completed gift?

- A) Direct Mail
- B) Online
- C) Major Gifts
- D) Event
- E) Telephone

**Q3.** Of the donors who made at least one completed gift in 2024, what percentage also made at least one completed gift in 2025, to one decimal place?

- A) 58.3%
- B) 51.6%
- C) 32.5%
- D) 52.6%
- E) 50.3%

## How to submit

Create a Word document (.docx) containing only your answers, one per line, in this format:

```
Q1: A
Q2: B
Q3: C
```

Upload it in the **cover letter** field of your application.
