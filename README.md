# Development-company-Cline-Vs-code
optimized automation agents for development, workflow orchestration, and AI task handling, designed for Cline VSCode integration, local execution, and scalable agent-based productivity systems with modular design.

# Batch Runner Guide

This package includes two Windows `.bat` runners.

## First-Time Requirement
Install and authenticate Cline CLI once:

```bat
npm install -g cline
cline auth
```

Make sure Cline is configured with your current provider/model, such as OpenAI Codex with GPT-5.4.

## Developer Side
Use this when creating a NEW project from one idea:

```bat
run_developer_side.bat
```

What it does:
1. Asks for your website/app idea.
2. Creates a new project folder on your Desktop.
3. Copies all agents into that project.
4. Opens VS Code if `code` command is available.
5. Starts Cline CLI in YOLO mode.
6. Builds, tests, audits, improves, packages, and prepares buyer handoff.

## Buyer / Client Side
Use this when implementing an ALREADY-BUILT bought/delivered project on a client machine/server:

```bat
run_buyer_client_side.bat
```

What it does:
1. Asks for the delivered project folder path.
2. Copies setup and verification agents into that project.
3. Opens VS Code if available.
4. Starts Cline CLI in YOLO mode.
5. Installs/configures/runs/verifies the existing app.
6. Creates `BUYER_SETUP_REPORT.md` and `BUYER_VERIFICATION_REPORT.md`.

## Important Safety Note
YOLO mode auto-approves actions. Use this only inside project folders you trust.
Do not run buyer-side setup on production servers unless you understand the risks.
