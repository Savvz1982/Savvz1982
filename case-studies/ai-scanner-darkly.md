# AI Scanner Darkly — Examiner-Led Media Authenticity Review

**Software initiative:** Windows desktop media-forensics workbench  
**Current maturity:** Private alpha/development candidate — not an approved operational or Store release  
**Public source code or downloadable binary:** Not available

## The problem

Image authenticity assessment is not a single AI score. Examiners need to distinguish provenance, metadata, media-structure observations, possible manipulation signals and unsupported inferences, while remaining in control of source evidence and the final report.

AI Scanner Darkly is a local-first investigation workbench pursuing that outcome. The product separates the examiner interface, evidence inspection and research/learning functions; nothing in this case study asserts a validated synthetic-media detection accuracy.

## My contribution

I guide requirements, investigator workflows, usability, evidence-integrity expectations and acceptance criteria as part of owner-directed APEX forensic software development. Source implementation has used AI assistance, with measurable testing, separate verification and eventual examiner acceptance required before operational claims.

## What is present in the current development UI

- A native PySide6/Qt Home workspace, Quick Inspect and case-oriented navigation.
- Examiner view with source selection, image canvas, magnification and content/provenance panels.
- Visible differentiation between **not checked**, **research-only** and actual examination results.
- Navigation to Batch Triage, Learning Vault, Corpus Manager and Training Control functions.

Presence of a menu or control does **not** by itself prove its downstream capability, model accuracy or distribution readiness.

## Authentic visual evidence: reviewed, not publicly posted

A successful Windows Actions run on November 16, 2026 produced **six real native Qt empty-state renders** at 1366×768, 1920×1080 and 2560×1080, covering Home and Examiner. Their SHA-256 digests were verified against the action's visual receipt. The captures used **no case or evidence media**, showed **no detection scores**, and were generated through an offscreen Qt child viewport—not a real end-user desktop installation.

The files are in a **private owner-review pack**. They are not public screenshots until image/caption and asset-rights review is complete. The workflow image used by this profile is **illustrative**, not a capture.

## Verification and limitations

Automated Windows native UI acceptance and forensic regression workflows passed at the observed development head. That does not establish independent forensic validation, AI detector accuracy, real desktop/top-level behavior, installed MSIX acceptance, publisher signing, safe downloading or Store qualification.

Before any field use or public download, independent security, rights, image safety, model quality and examiner acceptance remain necessary.

## What this demonstrates

Product requirements that prioritize evidence provenance, explainability, examiner agency and separating research claims from validated results. This is a development initiative, not an employer-endorsed investigation instrument.

[Back to my professional GitHub profile](../README.md)
