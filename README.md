# ui-ux-experiments

UI/UX landing experiments and interface prototypes built with OpenClaw.

A repo for building, storing, and reusing landing page styles.

## Goal
When Sebastian says:

- "make me a landing in the style of X"
- "reuse that dark premium style"
- "iterate on the last aesthetic"

we should not start from zero.

This repo stores:
- style references
- extracted style traits
- reusable templates
- UI/UX review notes
- screenshots and future visual comparisons

## Structure

- `style-db/references/` → raw references and notes
- `style-db/examples/` → normalized style entries
- `style-db/components/` → reusable component ideas/patterns
- `templates/` → actual landing implementations
- `UI_UX_REVIEW_PROCESS.md` → mandatory review loop

## Workflow

1. Add a new reference under `style-db/references/`
2. Extract its traits into `style-db/examples/`
3. Build/iterate a landing in `templates/`
4. Run desktop + mobile review
5. Save lessons back into the style DB

## Naming rule
Use descriptive IDs like:
- `dark-editorial-rain`
- `minimal-product-glow`
- `luxury-dark-glass`

So later we can say: "build this in the style of dark-editorial-rain".
