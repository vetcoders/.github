# `.github`

GitHub organization profile repository for [vetcoders](https://github.com/vetcoders).

GitHub renders [`profile/README.md`](profile/README.md) as the public org landing page at <https://github.com/vetcoders>.

## Layout

```
.github/
├── profile/
│   ├── README.md          ← rendered as the org landing page
│   └── assets/
│       ├── hero.png       ← landing hero (rendered from source design)
│       ├── og.svg         ← 1200×630 social/Open Graph card
│       └── stack-diagram.svg
├── CODE_OF_CONDUCT.md     ← org-wide conduct, fallback for all repos
├── SECURITY.md            ← security reporting, fallback for all repos
└── LICENSE                ← MIT for *this* repo; per-repo licenses inside each product
```

## Editing

Files under `CODE_OF_CONDUCT.md`, `SECURITY.md`, `ISSUE_TEMPLATE/`, and `PULL_REQUEST_TEMPLATE.md` in this repo act as **organization-wide defaults** for every repo that does not define its own. Update with care.

The `profile/` path is mandated by GitHub's org-profile convention — moving it breaks the landing.

---

© 2024–2026 LibraxisAI
