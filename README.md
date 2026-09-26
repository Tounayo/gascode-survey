# Gascode survey

## Live links
- Respondent survey: https://gascode-market-survey.tounayodavido.chatgpt.site
- Owner results and downloads: https://gascode-market-survey.tounayodavido.chatgpt.site/admin
- Private response repository: https://github.com/Tounayo/gascode-survey-responses

The survey works on phones and computers, uses Gascode branding, and includes household and property-manager paths from the Optimized Market Research Questionnaire.

Responses are saved to a protected database. Sign in to the admin page with the survey owner's ChatGPT account, download CSV or JSON, and upload that file to the private response repository. This is a manual export workflow, not automatic GitHub synchronization. Do not put respondent files in this public repository.

## Source
Download and extract `gascode-survey-source.zip` for the complete source, dependency lockfile, database schema and migrations, and development instructions. It contains no live responses or credentials. The existing `index.html.html` is the old incomplete draft; use the live link above.

Validation passed: production build, TypeScript checks, both survey tracks, idempotent retries, incomplete-answer rejection, anonymous export denial, and owner CSV/JSON exports.
