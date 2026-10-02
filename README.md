# vdp-rs2repro

Authorized CodeRabbit VDP research fixture (own account `coderabbit-vdp-research2`, own repos only).
Purpose: F-RUNNERSINKS-02 independent-account reproduction of the base execution primitive (steps
1-4 of the existing PoC) from a second, unrelated GitHub account/org, to rule out artifacts specific
to the original test account.

The module in `mdx/` executes at review time via a markdownlint `customRules` entry and beacons a
runtime-generated marker only. It reads no credential and touches nothing outside this repository.
