# 🎓 Osmania University MBA Results Portal

### MBA (CBCS-DAY) · I Semester · February 2026

---

## 📌 What is this website?

This is a **student-friendly results portal** built for Osmania University MBA students.

The **official Osmania University result page** only shows your:
- ✅ Grades (O, A+, A, B+, B, C, FAIL)
- ✅ Pass / Fail / Promoted status

But it does **NOT show**:
- ❌ SGPA
- ❌ Percentage

**This portal fixes that!** — It shows your original result exactly as the university website shows it, and then **automatically calculates your SGPA and Percentage** right below it.

---

## 🚀 How to Use

### Step 1 — Open the website
Click the link shared by your college / classmates:
```
https://yourusername.github.io/osmania-results
```

### Step 2 — Enter your Hall Ticket Number
- Type your **12-digit hall ticket number** in the box
- Example: `216325672007`

### Step 3 — Click "Get Result"
- Your **official result** will appear exactly like the university website
- Below that, your **SGPA and Percentage** will be automatically calculated
- If you have any failed subject, a **red warning** will clearly show which subject failed

### Step 4 — Print (optional)
- Click the **🖨 Print Result** button to print or save as PDF

---

## 📊 How is SGPA Calculated?

Each grade has a **Grade Point** value:

| Grade | Meaning   | Grade Point |
|-------|-----------|-------------|
| O     | Outstanding | 10        |
| A+    | Excellent   | 9         |
| A     | Very Good   | 8         |
| B+    | Good        | 7         |
| B     | Above Average | 6       |
| C     | Average     | 5         |
| FAIL  | Failed      | 0         |

**SGPA Formula:**
```
SGPA = Total Grade Points Earned ÷ Total Credits (ALL subjects)
```

> ⚠️ **Important:** Even failed subjects are **included in Total Credits** but contribute **0 grade points**. This means a fail will pull your SGPA down.

---

## ✅ Example — All Subjects Passed

| Subject | Credits | Grade | Grade Point | Points Earned |
|---------|---------|-------|-------------|---------------|
| MB101   | 4.0     | B+    | 7           | 28.0          |
| MB102   | 4.0     | B+    | 7           | 28.0          |
| MB103   | 4.0     | B+    | 7           | 28.0          |
| MB104   | 4.0     | B     | 6           | 24.0          |
| MB105   | 4.0     | A     | 8           | 32.0          |
| MB106   | 3.0     | A     | 8           | 24.0          |
| MB151   | 1.0     | O     | 10          | 10.0          |
| **Total** | **24.0** | —  | —           | **174.0**     |

```
SGPA = 174.0 ÷ 24.0 = 7.25
```

---

## ❌ Example — One Subject Failed

When a student fails a subject (e.g. MB104 — Statistics for Management):

| Subject | Credits | Grade | Grade Point | Points Earned |
|---------|---------|-------|-------------|---------------|
| MB101   | 4.0     | B+    | 7           | 28.0          |
| MB102   | 4.0     | B+    | 7           | 28.0          |
| MB103   | 4.0     | B+    | 7           | 28.0          |
| MB104   | 4.0     | **FAIL** | **0**    | **0.0** ← 0 points but credits still counted |
| MB105   | 4.0     | A     | 8           | 32.0          |
| MB106   | 3.0     | A     | 8           | 24.0          |
| MB151   | 1.0     | O     | 10          | 10.0          |
| **Total** | **24.0** | —  | —           | **150.0**     |

```
SGPA = 150.0 ÷ 24.0 = 6.25
```

> The failed subject's **4 credits** are still counted in the denominator (24), but it contributed **0 points** — this is what pulls the SGPA down compared to if you had passed all subjects.

---

## 📈 How is Percentage Calculated?

```
Percentage = (SGPA − 0.5) × 10
```

**Examples:**

| SGPA | Calculation          | Percentage |
|------|----------------------|------------|
| 6.25 | (6.25 − 0.5) × 10   | **57.5%**  |
| 7.00 | (7.00 − 0.5) × 10   | **65.0%**  |
| 7.25 | (7.25 − 0.5) × 10   | **67.5%**  |
| 7.50 | (7.50 − 0.5) × 10   | **70.0%**  |
| 8.00 | (8.00 − 0.5) × 10   | **75.0%**  |
| 8.50 | (8.50 − 0.5) × 10   | **80.0%**  |
| 9.00 | (9.00 − 0.5) × 10   | **85.0%**  |
| 10.0 | (10.0 − 0.5) × 10   | **95.0%**  |

> ⚠️ **Note:** The correct formula is `(SGPA − 0.5) × 10` — NOT the simple `SGPA × 10`.

---

## ⚠️ What Happens if I Have a Backlog?

If you have failed a subject, this portal will:

1. Show a **red warning banner** clearly mentioning which subject you failed
2. Show the failed subject in the breakdown table highlighted in red
3. Calculate SGPA **correctly** — including the failed subject's credits in the denominator with 0 grade points
4. Remind you to appear for the **supplementary / backlog examination**

---

## ❓ Frequently Asked Questions

**Q: Is this the official Osmania University website?**
> No. This is an **unofficial student-built tool**. The result data is fetched directly from the official Osmania University server (`osmania.ac.in`), so the result shown is 100% accurate. Only the SGPA and Percentage calculation is added by this portal.

**Q: Is my hall ticket number safe?**
> Yes. Your hall ticket number is only used to fetch your result from Osmania's server — the same way you'd enter it on the official website. It is not stored anywhere.

**Q: Why does my SGPA go down if I fail a subject?**
> Because the failed subject's credits are still counted in the total credits (denominator), but it contributes 0 grade points. This reduces your SGPA. For example, failing a 4-credit subject means 4 credits add to your total but contribute 0 points.

**Q: The official website doesn't show SGPA — is this calculation correct?**
> The SGPA calculation follows the standard CBCS grading formula. Failed subjects contribute 0 grade points but their credits are included in the total credits denominator. The percentage conversion `(SGPA − 0.5) × 10` is the standard formula used for Osmania CBCS results.

**Q: My result is not showing / showing an error. What do I do?**
> - Make sure you entered exactly **12 digits**
> - Double-check your hall ticket number from your admit card
> - Try again after a few minutes (the university server may be busy)

**Q: Which results does this portal support?**
> Currently supports: **MBA (CBCS-DAY) I Semester Regular Examination — February 2026**

---

## 🏛️ Credits & Acknowledgements

### Osmania University
> **All result data displayed on this portal is the sole property of Osmania University, Hyderabad.**
>
> The result information is fetched directly and exclusively from the **official Osmania University server** at [osmania.ac.in](https://www.osmania.ac.in). We do not store, modify, or tamper with any result data. Full credit for the result content goes to **Osmania University**.

| | |
|---|---|
| 🏛️ **University** | Osmania University, Hyderabad |
| 🌐 **Official Website** | [www.osmania.ac.in](https://www.osmania.ac.in) |
| 📋 **Result Source** | Osmania University Examination Branch |
| 📄 **Data Ownership** | © Osmania University — All Rights Reserved |

> This portal is purely a **student convenience tool** that adds SGPA and Percentage calculation on top of the officially published result. The underlying result data belongs entirely to Osmania University.

---

## ⚠️ Disclaimer

- This portal is built **by students, for students**
- Result data is fetched **live from the official Osmania University server**
- SGPA and Percentage are calculated using the standard CBCS formula
- This is **not affiliated with Osmania University** in any official capacity
- For any discrepancies in your result, please contact your college / university directly

---

*Built with ❤️ for Osmania University MBA Students · 2026*

*Result data © Osmania University, Hyderabad — All Rights Reserved*
