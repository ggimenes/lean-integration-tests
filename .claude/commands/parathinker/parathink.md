---
description: "Multi-Path Thinking Orchestrator - Analyzes problems through 8 independent reasoning approaches then synthesizes optimal solution"
---

# Multi-Path Problem Solving Orchestrator

## Overview

This workflow implements the ParaThinker approach for overcoming AI tunnel vision by generating 8 independent reasoning paths before reaching a consensus solution.

## CRITICAL EXECUTION PROTOCOL

You MUST execute commands in TWO sequential batches within a SINGLE response:

**BATCH 1:** All 8 thinking commands together  
**BATCH 2:** Consensus command immediately after

**DO NOT STOP** after batch 1. Both batches must execute in one continuous message.

---

## Step 1: Problem Preparation

Clearly restate the user's problem or requirement.

**Problem Statement**: [Restate the user's problem clearly and specifically]

---

## Step 2: Invoke All 8 Thinking Paths (First Batch)

Copy and execute all 8 SlashCommand invocations in a single function_calls block:

-   `/parathinker:think-analytical`
-   `/parathinker:think-creative`
-   `/parathinker:think-critical`
-   `/parathinker:think-practical`
-   `/parathinker:think-theoretical`
-   `/parathinker:think-user-centric`
-   `/parathinker:think-systems`
-   `/parathinker:think-iterative`

All 8 must be invoked together using the SlashCommand tool in parallel.

---

## Step 3: Invoke Consensus Synthesis (Second Batch)

**IMMEDIATELY after** the 8 thinking paths complete, invoke the consensus command:

-   `/parathinker:multipath-consensus`

This synthesizes all 8 perspectives into a unified optimal solution.

---

## Step 4: Present Final Solution

The consensus output will provide:

-   Executive summary of the synthesized solution
-   Key insights from each thinking approach
-   Implementation roadmap

---

## Quality Assurance

-   Each thinking approach operates independently
-   Consensus receives all outputs without bias
-   Fresh context prevents tunnel vision

**CRITICAL REMINDER:** Both batch 1 (8 commands) and batch 2 (consensus) must execute in the SAME response. Do not stop after batch 1.
