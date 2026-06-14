# PulsiForms

**Certified Visual Compiler for WinForms PowerShell GUIs**

> Stop writing WinForms by hand. Design visually. Export certified PowerShell.

-----

## The Problem

Every Windows IT administrator has been there — you need a simple GUI tool for your team, and you end up spending hours writing WinForms boilerplate in PowerShell by hand. The result is untested, uncertified, and breaks in production.

Existing tools either generate **probable code** (LLMs, templates) or require a **full development environment** (PowerShell Studio). Nothing in between.

-----

## The Solution

PulsiForms is a **certified visual compiler** — drag, drop, configure, export. The output is not just generated code. It is **certified** PowerShell.

- **Visual designer** — build your WinForms GUI without writing a single line
- **PF-Script DSL** — 22 high-level cmdlets (`Show-PF`, `Ask-PF`, `Validate-PF`, `Pick-PF`…) that compile to native WinForms
- **PFSyntaxGuard** — 189 certification rules across L1/L2/L3 analysis layers, 100% precision/recall
- **Zero runtime dependency** — the exported `.ps1` runs standalone on any Windows machine, no browser, no server, no install

-----

## Certified Code vs Probable Code

|                      |LLM / Template|PulsiForms       |
|----------------------|--------------|-----------------|
|Output                |Probable      |**Certified**    |
|Validation            |None          |189 PFR rules    |
|Runtime dependency    |Variable      |**Zero**         |
|WinForms errors caught|None          |**Automatically**|
|Dialect               |Mixed         |**PF-Script DSL**|

-----

## Key Specifications

- **189 PFR rules** across L1 / L2 / L3 analysis layers
- **22 PF-Script DSL cmdlets** — high-level abstractions compiling to native WinForms PS1
- **PFSyntaxGuard** — 1,528 tests, 100% precision, 100% recall on the oracle corpus
- **Export** — standalone `.ps1`, ready to run on any Windows machine
- **No installation required** — runs entirely in the browser, exports locally

-----

## Who Is It For

Windows IT administrators and sysadmins who need to build internal GUI tools quickly, without a development environment, without dependencies, and without risking broken code in production.

-----

## Use It

👉 **[pulsiforms.com](https://pulsiforms.com)**

No install. No signup required to explore. Open in your browser and start building.

-----

## Status

PulsiForms is a production-ready SaaS. The compiler, certification engine, and PF-Script runtime are closed-source.

This repository serves as the public reference and documentation hub.

-----

*Built by a solo developer. Designed for the Windows IT community.*
