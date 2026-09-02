EXPENSE TRACKER V11
Definitive transaction mode fix.

Root cause fixed:
A new transaction's Type change was writing into the editing object, which made the form think it was editing an existing transaction.

Now:
- Add always creates a fresh transaction.
- Changing Type on a new transaction never creates an edit state.
- Edit always remains Update Transaction.
- Changing Type while editing an existing transaction is supported.
- Search/render fixes retained.
- V11 cache version added.

Update ALL files in GitHub Pages and commit. Wait 1-2 minutes, then open the GitHub Pages URL in Safari.
Do not clear Safari website data.
