# Client Work Workflow

## Onboarding a new client
1. Copy `clients/_template/` and rename it to the client's name.
2. Fill in the client `README.md` and `01-brief/brief.md`.
3. Add logos and fonts to `02-brand/`, and fill in `brand-guide.md`.

## Monthly cycle
1. **Plan:** Create this month's content calendar in `03-content-calendar/`.
2. **Write:** Draft captions in `04-captions/`, then grammar-check them.
3. **Design:** Save work in progress to `05-designs/drafts/`.
4. **Approve:** Send to the client. Move approved files to `05-designs/final/`.
5. **Post:** Tick the "Posted" box in the content calendar.
6. **Report:** Add the monthly performance or ads report to `06-reports/`.

## Saving work to GitHub
```bash
git add .
git commit -m "ClientName: December captions"
git push
```
