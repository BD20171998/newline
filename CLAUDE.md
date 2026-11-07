# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

# Project Rules

## Build & Test
- Always run `npm run test` before committing changes
- Use `npm run lint` to check code style

## Architecture
- Monorepo with Turborepo; never mix concerns across packages
- TypeScript strict mode; unused variables are errors
- All API endpoints return { data, error } shape

## Conventions
- Use the custom Logger module, never console.log
- Prefer named exports over default exports
- Error messages must be user-friendly, not stack traces

## Never Do
- Never modify files in the /config/production/ directory
- Never commit .env files or hardcoded secrets
- Never suggest or execute destructive commands (rm -rf, DROP TABLE, force push) without explicit confirmation
- Never read files outside of the project directory /Users/my_mac/Desktop/newline without first asking permission
