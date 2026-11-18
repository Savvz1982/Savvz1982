# DriveSeal — Evidence Delivery and Independent Verification

**Software initiative:** Windows forensic-media preparation and evidence delivery  
**Current maturity:** Controlled private development / beta candidate — not field-released  
**Public source code or downloadable binary:** Not available

## The problem

A case agent delivering digital evidence and a forensic examiner validating it need an understandable workflow that reduces wrong-drive selection, unexpected media formatting and unverifiable handoffs. DriveSeal is designed around **explicit device identity, clear operator choices and independently checkable output**, rather than assuming a successful file copy proves evidence integrity.

## My contribution

I direct product requirements, task-level usability priorities and acceptance expectations for the APEX forensic software portfolio. Engineering has been developed with AI assistance and must be judged on actual source, tests, Windows acceptance and independent examiner review—not on a polished interface alone.

## What the development work covers

- Task-oriented preparation, transfer and standalone verification, including distinct workflows rather than one complicated settings screen.
- Conservative defaults, visible dry-run / live-action distinctions, and physical-device identification before sensitive operations.
- BitLocker-protected preparation as an explicitly selected mode, with recovery-custody considerations.
- Evidence manifests and optional strict-inventory verification, with integrity separate from authenticity or full chain of custody.
- Operator-readable handoff and report concepts that do not imply recipient acknowledgement before one exists.

These are development capabilities and engineering directions. They are **not** claims that every workflow has passed real-media acceptance or deployment qualification.

## What has actually been verified

The private development branch has a successful exact-source Windows build/test workflow at its observed development head on November 18, 2026. This is an **engineering gate**, not an independent field acceptance or licensed release. Physical disposable-drive tests, accessibility at Windows scaling settings, real interruption/cancellation behavior and examiner acceptance remain open.

No real evidence drives, case identifiers or recovery secrets were used to prepare this public case study.

## Visual material

The [portfolio workflow diagram](../assets/forensic-workflows.svg) is **illustrative, not a DriveSeal application screenshot**. A sanitized capture from a genuinely running Windows build has **not yet been obtained and approved for publication**. It will be added only after verification that the exact build and visible information are appropriate for public release.

## What this demonstrates

This project reflects a product-engineering approach centered on forensic risk, usability for novices and experts, operational integrity and truthfully labelled verification. It is independent of my law-enforcement employment and is not represented as an agency-approved tool.

[Back to my professional GitHub profile](../README.md)
