# 💰 Budget Tracker

A simple, private budget tracker that runs in your browser. Log income and expenses, set monthly limits per category, and always know how much you have left to spend.

No account, no server, no install: it's a single `index.html` file.

## Features

- **Left to spend:** your remaining budget for the month, plus a daily amount for the days left
- **Budget pace:** compares how much of your budget is used with how much of the month has passed
- **Category budgets:** set a monthly limit per category; bars turn amber when you're spending fast and red when you're over
- **Quick entry:** expense or income, amount, category, date, optional description
- **Monthly items:** mark rent, salary or subscriptions as repeating and add them to the next month in one click
- **Spending chart:** your spending through the month against an even pace to your budget
- **Transactions:** grouped by day, with search, category filter, edit, and delete with undo
- **Any month:** browse past months with the arrows at the top
- **Currencies:** ZAR, USD, EUR, GBP, NGN, KES, BWP, NAD, AUD, CAD, INR, JPY
- **Backups:** export to CSV or a full backup file, and import them again
- Light and dark mode, works on phones

## Use it

Double-click `index.html` to open it in your browser. Or put it online with GitHub Pages (below) and open it from anywhere.

## Put it online with GitHub Pages

1. Create a new **public** repository on GitHub.
2. Click **uploading an existing file**, drag in `index.html`, `README.md` and `LICENSE`, then click **Commit changes**.
3. Go to **Settings → Pages**. Under **Source** choose **Deploy from a branch**, select **main** and **/ (root)**, then click **Save**.
4. After a minute or two your tracker is live at `https://<your-username>.github.io/<repo-name>/`.

## Where your data is stored

Everything you enter is saved in your browser's local storage on the device you're using. Nothing is sent anywhere.

That also means:

- Your phone and computer each keep their own separate data.
- Clearing your browser data deletes your budget.

Use **Export backup** at the bottom of the page regularly, and **Import** to restore it or move it to another device.

## Importing from a CSV

Your CSV needs a header row. `date` and `amount` are required; the rest are optional.

| Column        | Example              |
|---------------|----------------------|
| `date`        | `2026-10-23` (YYYY-MM-DD) |
| `type`        | `expense` or `income` (defaults to expense) |
| `category`    | `Groceries` (new categories are created automatically) |
| `amount`      | `450.00` |
| `description` | `Weekly shop` |
| `monthly`     | `yes` for repeating items |

Tip: export a CSV first to see the exact format.

## Keyboard shortcut

Press **N** anywhere on the page to jump straight to the amount field.

## License

[MIT](LICENSE)
