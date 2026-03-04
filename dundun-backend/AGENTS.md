# DawnDone Backend Agent Guide

## Goal
Implement backend features for DawnDone based on `docs/WorkProofPay_PRD_v1.4.md`.

## Current Scope
- Feature-first skeleton modules
- JWT login/auth baseline
- P0-first delivery (WorkProof, Wage Shield, Documents, Remittance)

## Rules
- Keep package structure per feature (`api/service/repo/model/adapter`).
- Do not hardcode secrets; use env/config.
- Keep security endpoints explicit in `SecurityConfig`.
- Add tests for auth and business-rule changes.

## Run
- `./gradlew bootRun`
- `./gradlew test`
