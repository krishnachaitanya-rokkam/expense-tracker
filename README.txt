EXPENSE TRACKER V3 — iCloud Numbers bridge

iCloud Numbers cannot be written to directly by a normal PWA. V3 includes a button that invokes an iPhone Shortcut named "Expense to Numbers".

Create that Shortcut:
1. Open Shortcuts > + and name it Expense to Numbers.
2. Use Shortcut Input as text.
3. Split Text using " | " as the separator.
4. Add the Numbers action that adds a row to the bottom/top of a chosen iCloud Numbers table.
5. Map the six values to Date, Merchant, Category, Payment, Amount, Notes.
6. Save.

Then tap Numbers in the app after saving an expense. The latest transaction is passed to the Shortcut and can be appended to Numbers.

The app still works offline and keeps a local copy.
