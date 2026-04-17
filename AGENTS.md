# AGENTS.md

## 1. Purpose
This repository stores multi-effects manuals for guitar/bass devices in a format that is easy to:
- maintain by one owner,
- update with AI assistance,
- publish on GitHub-based static web frontends.

Primary goal: keep docs consistent, machine-readable, and safe from hallucinated specs.

## 2. Repository Contract
Canonical structure:

```text
brands/<brand-slug>/<model-slug>/
  manual.en.md
  manual.ko.md
  summary.md
  assets/
```

Indexes:
- `indexes/brands.md`
- `indexes/models.md`

Templates:
- `_templates/model/*`

## 3. Agent Scope
Agents may:
- add new model folders,
- structure user-provided manuals,
- translate EN <-> KO manuals,
- enrich `summary.md` from provided sources,
- update indexes.

Agents must NOT:
- invent prices/specs/release dates,
- overwrite unrelated models,
- change folder/file naming conventions,
- remove source-attribution context.

## 4. Naming Rules (Strict)
- Brand/model folder names: lowercase kebab-case.
- Required files per model:
  - `manual.en.md`
  - `manual.ko.md`
  - `summary.md`
- No alternate names like `english.md`, `kr.md`, `specs.md`.

## 5. Frontmatter Rules
### 5.1 `manual.en.md` / `manual.ko.md`
Use frontmatter:

```yaml
---
brand: "<brand-slug>"
model: "<model-slug>"
language: "en|ko"
source: "..."
firmware: "..."
last_updated: "YYYY-MM-DD"
---
```

### 5.2 `summary.md`
Use frontmatter:

```yaml
---
brand: "<brand-slug>"
model: "<model-slug>"
category: "multi-fx" # or bass-multi-fx
release_year: null
status: "active" # active | discontinued
last_updated: "YYYY-MM-DD"
---
```

## 6. Manual Editing Policy
When converting raw manual text:
1. Preserve technical meaning.
2. Fix OCR/line-break corruption for readability.
3. Keep section hierarchy explicit (`##`, `###`).
4. Keep lists/tables deterministic for frontend rendering.
5. Preserve model/effect names as product terms.

If ambiguous:
- keep original term in English,
- add clear Korean explanation,
- do not guess hidden values.

## 7. Translation Policy (EN/KO)
- Use natural Korean, but keep gear terms recognizable.
- Keep units/symbols exactly (`dB`, `kHz`, `1/4" TS`, `DC 9V center-negative 500mA`).
- Keep mode names/code-like labels in backticks.
- Do not omit warnings/safety information.

## 8. Summary Policy
`summary.md` should include:
1. Overview
2. Main features
3. Key specs
4. Price range
5. Review summary
6. One-line verdict
7. References

Hard rule:
- If price/spec is not verified, write `확인 필요`.
- Never fabricate market data.

## 9. Effect List Policy
For effect-heavy models:
- Do not over-compress effect lists.
- Keep module-level grouping (`FX1/FX2`, `AMP`, `CAB`, `EQ`, `MOD`, `DLY`, `RVB`, etc.).
- Include each effect name with a one-line description.
- Preserve common parameter blocks where available.

## 10. Index Update Rule (Mandatory)
Any new model must update both:
- `indexes/brands.md`
- `indexes/models.md`

A model addition is incomplete without index updates.

## 11. Quality Gate Checklist
Before commit, agents must verify:
- [ ] Folder path matches slug rules.
- [ ] 3 required files exist for model.
- [ ] Frontmatter is present and valid YAML.
- [ ] No invented numbers (price/spec/date).
- [ ] `summary.md` follows section contract.
- [ ] Both index files updated.
- [ ] Markdown renders cleanly (tables/lists/headers).

## 12. Commit Convention
Recommended commit style:
- `Add <brand> <model> manuals (EN/KO) and summary`
- `Expand <model> effect list details in EN/KO manuals`
- `Refactor repository structure for brand/model schema`

## 13. Website Readiness Notes
This repo is intended for static frontend consumption.
Keep content parser-friendly:
- stable filenames,
- stable frontmatter keys,
- predictable section headers,
- no random schema drift.

If schema changes are needed, update:
- `_templates/model/*`
- `README.md`
- this `AGENTS.md`
- existing model docs (migration).

## 14. Single Source of Truth
Priority order:
1. User-provided original text / official manufacturer docs
2. Existing model manual files
3. Summary interpretations

When conflicts occur, prefer source text and mark unresolved points explicitly.
