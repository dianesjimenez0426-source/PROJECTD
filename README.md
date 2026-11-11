# PROJECTD

Client work repository: briefs, brand guides, content calendars, captions, designs and reports, organized by client.

## Folder structure

```
PROJECTD/
├── clients/
│   └── _template/              # Copy this for each new client
│       ├── 01-brief/           # Client brief and goals
│       ├── 02-brand/           # Logos, fonts, brand guide
│       ├── 03-content-calendar/# Monthly posting plans
│       ├── 04-captions/        # Monthly captions
│       ├── 05-designs/
│       │   ├── drafts/         # Work in progress
│       │   └── final/          # Approved files
│       └── 06-reports/         # Performance and ad reports
├── assets/                     # Shared agency assets (logo, templates)
├── docs/
│   ├── workflow.md             # Onboarding and monthly process
│   └── naming-conventions.md   # How to name files and folders
├── .editorconfig
├── .gitignore
└── README.md
```

## Adding a new client

1. Copy `clients/_template/` and rename it, e.g. `clients/client-name/`.
2. Fill in the client `README.md`, the brief and the brand guide.
3. Follow the monthly cycle in [docs/workflow.md](docs/workflow.md).

## Getting started

```bash
git clone https://github.com/dianesjimenez0426-source/PROJECTD.git
cd PROJECTD
```

Save your work:

```bash
git add .
git commit -m "Describe your change"
git push
```
