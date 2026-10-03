# antiform.as

Antiform's public site. Plain HTML, each page with its own inline `<style>`; no build
step and no dependencies. `CNAME` maps the repository to antiform.as.

| Path              | Page                             |
| ----------------- | -------------------------------- |
| `index.html`      | Antiform                         |
| `flimmer/`        | Flimmer for merchants, Norwegian |
| `flimmer/faq/`    | Flimmer FAQ, Norwegian           |
| `flimmer/en/`     | Flimmer merchant guide, English  |
| `flimmer/en/faq/` | Flimmer FAQ, English             |

## Rules

- **Short by default.** Nobody reads this for pleasure, so length is a cost. Say the
  load-bearing thing and stop. A page past roughly one screen gets cut, not restructured.
- **The source of truth is in `antiform-as/flimmer`:** `docs/operations/vipps-merchant-guide.md`
  and `docs/operations/vipps-merchant-faq.md`. The English pages track them closely. A
  fact changes there first, then here, in both languages at once.
- **Norwegian is written, not translated.** Same facts as the English, not the same
  sentences, in roughly a third of the words. Em-dashes standing in for full stops, and
  announcing clauses like "to ting er verdt å si rett ut", are the tell of a translation.
- **Never break a linked URL.** The submitted Vipps checklist links to
  `antiform.as/flimmer/en/#apply`, `…/en/#configure` and `…/en/faq/`. Keep those paths
  and `id`s, and keep what they point at matching the documentation: a link to a page
  that contradicts it is worse than no page.
- **Flimmer is the platform, Antiform is the company.** Never _tenant_ or _leietaker_ on
  these pages.

The full rules are in `antiform-as/flimmer`, `AGENTS.md` § Antiform's public content.
