# Work Order NEX-PROFILE-WO-001 — NexLabs GitHub Profile

**Status:** Owner-authorized; execution through a Draft pull request  
**Risk:** LOW  
**Target:** csn1985/csn1985, the profile repository for @csn1985

## Objective

Create a polished English-language GitHub profile presentation for NexLabs Technology, using the approved Precision Blades mark, a near-black field, restrained lime accents, concise copy, and a small number of meaningful emoji icons.

## Context and source state

- Owner authorization is recorded in docs/BOOTSTRAP.md.
- Baseline main commit: f90ec11c26cec9a4dfe5675ea89fc9961788eb5e.
- The repository is public. It currently contains only docs/BOOTSTRAP.md; no profile README or open pull request exists.
- The profile README is the repository surface rendered on the GitHub account page.
- The official logo source is KayzenRoot/nexlabs-website at e14cfbe4660b076db85e7e529befffe17a098cd1, file public/brand/nex-labs-technology-extended-dark.svg, blob 51e61d8f98903ccf6b29e504ce5c9df1ab691ec1.
- Corporate brand and public-copy sources govern names, logo geometry, factual claims, and approved capability descriptions.

## Scope

- Add README.md with the English corporate presentation.
- Add assets/nexlabs-profile-banner.svg. It uses the approved mark geometry and white mark treatment, with a profile-specific near-black/lime presentation.
- Add this Work Order, its Evidence Bundle, versioned canonical Source Pack, Context Lock and a byte-identical approved logo copy under docs/ and assets/.
- Open a Draft PR against main after reviewing the diff and evidence.

## Out of scope

- Direct changes to account settings such as name, bio, location, company, website field, avatar, social links, or pinned repositories. The connected GitHub tools expose profile reading, but no account-profile update action.
- Renaming the account or changing repository visibility, issues, branch protection, or other settings.
- Modifying any product repository, the main NexLabs website source, domain/DNS, hosting, deployment, or production status.
- Claims about customers, funding, revenue, users, team size, deployments, awards, certifications, partnerships, metrics, or market leadership.
- Merge or direct commits to main.

## Sources to read

- docs/BOOTSTRAP.md and the target Source Pack in this repository.
- KayzenRoot/nexlabs-company @ main tree cbfa3e21a808622f4a3737b677277e4ca17ef30c and its corporate checkpoint, decisions and brand/public-proof authorities.
- KayzenRoot/nexlabs-company: .engineering/SOURCE-HIERARCHY.md, company/BRAND-SYSTEM.md, company/NAME-AND-MARK-USAGE.md, company/VISUAL-LANGUAGE.md, company/BRAND-VOICE-AND-PUBLIC-COPY.md, company/PUBLIC-WEBSITE-CONTENT-CONTRACT.md, company/PUBLIC-PROOF-AND-DISCLOSURE-POLICY.md, company/PUBLIC-ASSET-GOVERNANCE.md, and company/PUBLIC-PORTFOLIO-SCHEMA.md.
- KayzenRoot/nexlabs-website: .engineering/SOURCE-HIERARCHY.md, .engineering/CHECKPOINT.md, .engineering/DEPLOYMENT.md, .engineering/HOME-CONTENT-SPEC.md, and the approved logo asset listed above.

## Requirements and constraints

- Use the corporate name NexLabs Technology and the approved visual wordmark NEX LABS.
- Keep the Precision Blades mark geometry intact and recognizable; lime is a profile presentation accent, not a recoloring of the official mark.
- Use only capability and principle copy supported by the canonical public sources.
- Label the website link as source code because production deployment is not admitted in the current website checkpoint.
- Keep emoji usage restrained and semantic. Do not use fabricated stats, client logos, testimonials, or external proof.
- Preserve docs/BOOTSTRAP.md and all current repository settings.
- Keep all changes on the named feature branch and reviewable in a Draft PR.

## Acceptance criteria

1. README.md is in English, renders the company name and approved logo, explains the direction and focus areas, and links only to verified public repositories.
2. The banner is valid SVG, accessible by title/description, uses the approved mark path, and keeps lime outside the official mark.
3. Public copy contains no unsupported maturity, traction, customer, investment, or deployment claims.
4. The diff is limited to README.md, the banner, this Work Order, and its Evidence Bundle.
5. Evidence records the exact base, implementation/head commits, file hashes, checks performed, and any unavailable automation.
6. A Draft PR is opened against main. Do not merge it.

## Checks

- Verify the exact base and feature branch before writing.
- Validate the SVG structure and required accessibility nodes.
- Check README local asset paths and hyperlinks.
- Review the final changed-file list and patch against the acceptance criteria.
- Confirm no runtime test suite or CI workflow is present; report that accurately instead of inventing a passing check.

## Deliverables

- README.md
- assets/nexlabs-profile-banner.svg
- docs/work-orders/NEX-PROFILE-WO-001.md
- docs/evidence/NEX-PROFILE-WO-001-EVIDENCE.md
- docs/source-pack canonical files, docs/context-lock/NEX-PROFILE-WO-001.json and assets/official-nex-labs-technology.svg
- Draft PR with the final Evidence Bundle summary.

## Review format

Return an exact-head audit in Brazilian Portuguese with verdict APPROVED, CORRECTION REQUIRED, or BLOCKED. Cover source authority, copy truthfulness, logo provenance, diff scope, checks, limitations, and merge state.

## Stop condition

Stop before merge or any account-setting/website/deployment change. If the base/head drifts, required source changes, or a material brand/public-claim ambiguity appears, mark the Context Lock stale and block for revalidation.
