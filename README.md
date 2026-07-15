# Practical AI Auditing — the AI Audit Accelerator

A hands-on, end-to-end audit of a real (but fictional) AI system, released one domain a week
as part of the **AI Governance, Unpacked** series. Everyone talks about AI governance; this
shows **where and how you actually start on the ground**.

> **Everything here is synthetic.** The "Kannan's Virtual Bank" support assistant and all its
> data are fictional, built purely for AI-audit training. Educational accelerator, not a
> compliance guarantee — adapt before any real-world use.

## What's inside
| Folder | What it holds |
|--------|---------------|
| `app/` | The system under audit — Colab notebook (Gemini + Gradio) and requirements. |
| `data/` | The synthetic dataset and the bias & red-team probe sets. |
| `setup/` | The Environment Setup Guide — stand the app up from zero. |
| `workbook/` | The AI Audit Accelerator — the lean checklist. Grows one domain each week. |
| `guides/` | The weekly Field Guides — the "why" behind each domain. |
| `system-docs/` | The audited system's sample governance documents (Fact Sheet, RACI, register, data-flow, output catalogue). |
| `evidence/` | Audit evidence, per domain (released as each week runs). |
| `findings/` | Findings register and the eventual audit report. |

## Quick start
1. Read `setup/AI_Audit_Environment_Setup_Guide` and follow it.
2. Open `app/KV_Support_Bot.ipynb` in Google Colab.
3. Add a paid Gemini key as the Colab secret `GEMINI_API_KEY`, upload `data/`, run the cells.
4. Open the week's workbook tab and work the checks.

## Released weekly (v05 … v16)
One audit domain per week, Weeks 05–16, toward a complete toolkit. Each week is tagged as a Release.

## Author
**Kannan K** — AI Governance & Cybersecurity Leader. Part of *AI Governance, Unpacked*. #AIGovernanceUnpacked
