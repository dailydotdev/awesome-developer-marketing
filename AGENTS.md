# Local Agent Notes

## Public Repo Rules

- Never include private business goals, internal strategy, or non-public objectives in commit messages, PR titles/bodies, issues, or any other public artifacts.
- Keep all public-facing explanations neutral and implementation-focused.

## Linting

- Always run `npx awesome-lint` locally before committing changes to `README.md`. CI runs `awesome-lint` and will block PRs that fail.
- The `awesome-spell-check` rule enforces capitalization of known terms (e.g., "Expo" not "expo", "GitHub" not "github"). Check descriptions for proper casing of product and brand names.

## README Structure

- Each section in `README.md` follows the format: `- [Name](https://url) - One-sentence description ending with a period.`
- New entries go at the end of their respective section, before the next `##` heading.
- Descriptions should be concise, factual, and avoid marketing language or superlatives.
