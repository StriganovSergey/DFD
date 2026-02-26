# Development Framework Directive (DFD)
## Overview

DFD is a comprehensive set of universal rules for code generation, designed for use in software development projects across multiple languages (e.g., Python, C++, Go, PL/SQL, PowerShell, Bash) and platforms (e.g., Windows, Linux). It promotes resilient, maintainable, and production-ready code by enforcing best practices in areas like error handling, configurability, scalability, and idempotency.This framework is particularly useful for AI-assisted coding (e.g., with LLMs like Grok) to ensure consistent, high-quality outputs. 
Rules are categorized into blocks (e.g., Control, Preparation, Task Clarification), prioritized (CRITICAL, HIGH, MEDIUM, LOW), and applied at specific stages (Preparation, Setup, Data Processing, Integration, Finalization).
## Key Features
Strict Compliance: Mandatory adherence to rules, with self-review and user overrides for flexibility.
Task Alignment: Clarifies goals, proposes options with pros/cons, and identifies logic flaws/risks early.
Code Principles: Emphasizes separation of config/code, robust error handling, logging, and debug modes.
Verification & Output: Includes self-review, reports, and explanations for traceability.
Examples: Rules include positive ("good") and negative ("bad") examples to illustrate best/worst practices.
## Usage
As a Prompt for LLMs: Copy the full DFD into your AI prompt to guide code generation. Example: "Generate code following DFD rules for [task]."
For Developers: Reference in projects to standardize coding workflows.
Customization: Override rules via explicit user confirmation (e.g., for conflicts).
## Structure
Blocks: Group related rules (e.g., [BLOCK_CONTROL] for compliance, [BLOCK_TASK_CLARIFICATION] for decision strategies).
Application Order: Rules applied sequentially by stage.

