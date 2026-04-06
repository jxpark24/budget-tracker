Budget Tracker - Project Structure

1. Goal
This program helps track my spending and show where my money goes.
Main purpose: compare spending (food vs car vs others).

2. Data Structure
Each transaction will include:
- date (YYYY-MM-DD)
- type (income or expense)
- amount (number)
- category (food, car, rent, etc.)

Example:
{
  "date": "2026-04-06",
  "type": "expense",
  "amount": 15.5,
  "category": "food"
}

3. Storage
All transactions will be stored in a file (data.json).

4. Program Features (Version 1)
- Add transaction (income or expense)
- Show all transactions
- Calculate total balance

5. Program Features (Future)
- Daily summary
- Weekly summary
- Monthly summary
- Quarterly summary
- Category comparison like (car, cloth, living, food, hobies.. etc)
- Warning messages for high spending (it need to be compare with average of spending?)

6. Program Flow
- Start program
- Load data from file
- Show menu
- User chooses option
- Program processes input
- Save data if needed

7. Files
- main.py: program entry (menu and user interaction)
- storage.py: file read/write
- budget.py: calculations
- data.json: saved data
- structure.txt: project design

8. Notes
- Use Python
- Use JSON for storage
- Keep program simple first and expend it.