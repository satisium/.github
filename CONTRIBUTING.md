# Contributing to Satisium

Thank you for contributing to **Satisium**! Every product in the suite is built to be code-native, minimal, and zero-key bootable.

## Workflow
1. Fork or branch from `main` using short-lived branches (`feat/*`, `fix/*`, `chore/*`).
2. Use **`pnpm`** (Node 22+) to install dependencies:
   ```bash
   pnpm install
   pnpm dev
   ```
3. Follow **Conventional Commits** for commit messages and PR titles:
   - `feat:` new capability or user-facing feature
   - `fix:` bug fix
   - `refactor:` internal restructuring with no behavior change
   - `docs:` documentation updates
   - `chore:` tooling, dependencies, or CI
4. Run the full pre-flight check before opening a PR (with an empty `.env.local`):
   ```bash
   pnpm run doctor
   ```
5. Open a Pull Request targeting `main`. PRs are integrated via **Squash & Merge**, and branches are deleted immediately after merge.

## Community & Support
Join the community on Discord: https://discord.gg/xQ5cPHmT7
