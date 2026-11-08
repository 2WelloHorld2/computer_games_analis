# Project Specification — Video Game Sales Analysis

## Scope
Analyze historical video-game sales by platform, genre and market; explore association of user/critic reviews with sales and assess statistical hypotheses.

## Primary artifact
`project/main.ipynb`

## Expected workflow
- Inspect and clean supplied input data, retaining an explicit record of assumptions and limitations.
- Perform project-specific exploration, calculations and statistical/model evaluation reflected in the notebook.
- Produce reproducible charts, metrics and interpretations based on actually available data.
- Do not imply that exercise datasets, reported metrics or conclusions have been independently validated.

## Project-specific validation
Validate region-level sales totals, release years, missing platform/genre, duplicates and the assumptions of statistical tests. Distinguish association from causation.

## Engineering principles
- Maintain clear, reproducible analytical steps and document data assumptions; never fabricate outcomes, metrics or data.
- Use SOLID where meaningful for Python modules, DRY/KISS for notebook workflows, and pragmatic Clean Architecture separating input, validation, analysis/modeling and presentation.
- Prefer small focused functions and avoid speculative architecture, dependencies or changes outside the requested scope.
- Never hard-code credentials or commit private datasets, personal identifiers or notebook outputs containing sensitive information.
- Specifications reflect the actual implementation. Significant user-authorized behavior changes require a corresponding spec update.
- Run applicable lint and test checks when tools and dependencies are available; identify checks not run rather than claiming success.

## Change acceptance
1. Scope the requested change to relevant notebook(s), code, tests and spec.
2. Preserve existing analytical conclusions unless validated by new evidence.
3. Validate input assumptions and outputs; check for unexpected diffs.
4. Review security and test evidence before asking for approval to push.
5. Require explicit user authorization for publishing or destructive actions.
