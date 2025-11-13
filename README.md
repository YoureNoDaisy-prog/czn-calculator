Run Locally (Offline — Recommended)

Step 1: Save the File
Copy the full HTML code below
Paste into a text editor (Notepad, VS Code, etc.)
Save as: czn-calculator.html
Important: File name must end with .html


Step 2: Open in Browser

Double-click the file
It will open in your default browser
Done! Use it forever — even without internet

Works on: Chrome, Firefox, Edge, Safari, mobile browsers

# CZN Faint Memory Calculator

A responsive, local-first web tool to track Faint Memory costs for CZN character builds.  
Perfect for planning card limits across 3 characters without exceeding tier-based Faint Memory caps.

> No server. No tracking. All data stays in your browser.

---

## Features

| Feature | Description |
|-------|-------------|
| 3 Character Panels | Track up to 3 characters simultaneously |
| Tier Calculation | Base Tier + Nightmare (+1) + Codex (+1/+2) |
| Faint Memory Limit | `30 + 10 × (Effective Tier - 1)` |
| Smart Cost Breakdown | Visual cost per category |
| Progressive Costs | Duplications & Removals: `0 → 10 → 30 → 50 → 70+` |
| Vivid vs Faint Clarity | Forbidden cards & Character Epiphanies = **Vivid (0 Faint) |
| Safe / Warning / Danger Status | Real-time limit feedback |
| Save / Load / Export | `localStorage` + JSON export |
| Copy Panel | Copy single character JSON to clipboard |
| Clear / New Run | Reset individual or all panels |

---

## Cost Rules Summary

| Action | Faint Cost |
|------|-----------|
| Neutral Card | `+20` |
| Monster Card | `+80` |
| Common Epiphany | `+10` |
| Divine Epiphany | `+20` |
| Character Epiphany | `0` (Vivid) |
| Forbidden Card | `0` (Vivid) |
| Removal (non-char) | `0, 10, 30, 50, 70...` |
| Removal (character) | `+20` per removal (on top of base) |
| Duplication (any) | `0, 10, 30, 50, 70...` per dup |
| Conversion: Neutral | `+30` |
| Conversion: Monster | `+90` |
| Conversion: Other | `+10` |

---

## How to Use

1. Set Character Name – Click the title
2. Adjust Tier Settings:
   - Base Tier (1–10)
   - Nightmare (check for +1)
   - Codex (+1 or +2)
3. Enter Card Counts in each section
4. Watch the Cost Breakdown update live
5. Check Status:
   - 🟢 Safe: ≥20 pts remaining
   - 🟡 Close: 0–19 pts
   - 🔴 OVER: Negative!
6. Save / Export your build

---

## Free to Use

**You’re welcome to use, copy, modify, and share this code however you like** – no permission needed.

> *No license file is included. The code is released into the public domain (or under the most permissive terms your jurisdiction allows).*

---

*Feel free to fork, improve, or build on it!*
