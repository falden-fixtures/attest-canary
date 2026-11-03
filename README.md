# attest-canary

A public canary for the Falden fixture pack's witness, run on the 1.0 rehearsal's first date (R1,
Tue 2026-11-03) and archived the same day. It is synthetic and holds no work.

.github/workflows/attest.yml is, byte for byte, the attestation workflow the 1.0 subject repositories
carry. It runs here first because artifact attestations need a public repository on GitHub's Free, Pro
and Team plans, and the rehearsal's repositories are private. .github/workflows/never-starts.yml asks
for a runner nobody has, so its run never starts and the dispatcher's cancel is exercised.

The fixture pack's LIMITS names this repository and its id.

Copyright (c) 2026 Falden, Inc. Licensed under the MIT License (LICENSE).
