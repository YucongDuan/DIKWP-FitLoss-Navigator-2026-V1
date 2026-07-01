# DIKWP FitLoss Navigator 2026 V1

A standalone, offline-first prototype for safe fitness, fat-loss, habit design, progress evidence and human-reviewed coaching workflows.

## Quick start
Open `index.html` in a modern browser. No server, database, API key, account or network is required.

Optional CLI:

```bash
python tools/run_fitloss_plan.py examples/sample_client_profile.json --out outputs
```

## What it does

- estimates BMR/TDEE and a moderate energy-deficit target
- creates strength/cardio/NEAT guidance
- registers medical and behavioral red flags
- uses a DIKWP D/I/K/W/P/R loop for fat-loss behavior
- keeps Progress Evidence Ledger and AI Use Log
- creates Action Tickets and a FitLoss Passport

## What it must not do

- diagnose diseases
- prescribe weight-loss drugs, injections, surgery or medical diets
- treat eating disorders
- provide pediatric, pregnancy or postpartum weight-loss prescriptions
- clear users with chest pain, fainting, severe breathlessness or uncontrolled chronic disease for exercise
- generate body-shaming or extreme dieting instructions

## Design lineage
The prototype extends the DIKWP Evidence Ledger / Action Ticket / Human Review / Static Boundary Audit pattern into fitness and fat-loss coaching.
