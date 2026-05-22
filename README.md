# VeldLink-2026

EcoSync 2026 — offline-first livestock sync system for SADC farmers.

## Branch: fix-sync-logic

This branch was created to isolate the fix for the Sync Logic failure causing
data loss during mid-transmission power outages on remote EdgeGateways. It
allows the bug to be resolved without interrupting parallel development on the
stable `main` branch.
