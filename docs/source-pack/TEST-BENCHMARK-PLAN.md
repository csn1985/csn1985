# Test and Benchmark Plan

1. Confirm account, repo, base SHA and unchanged settings.
2. Byte-compare official logo to website asset at e14cfbe4660b076db85e7e529befffe17a098cd1.
3. Validate both SVGs (XML syntax, active-content/external-reference allowlist).
4. Validate local README asset paths and existing GitHub outbound links.
5. Audit English copy, claim accuracy, accessible text and foreground/background contrast.
6. Check changed-file allowlist, Source Pack completeness, base/head diff and candidate readback.
7. Independently audit exact PR HEAD, rulesets, required statuses and approval.
8. Only after normal merge: verify main README and rendered profile. No runtime benchmark applies.
