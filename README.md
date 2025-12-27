# SFA — Structural Flow Analytics

This repository contains the **logic-only core libraries** of the SFA framework.

SFA is an institutional-grade trading engine focused on:
- structural flow
- liquidity events
- regime detection
- market continuity vs reversal

## Purpose of this repository

This repository exists for:
- technical traceability
- version control
- future audits
- logic freezing of validated modules

It does **NOT** contain:
- visual indicators
- drawings or chart objects
- complete trading strategies
- execution logic
- monetization logic

## Architecture

The SFA framework is structured in layers:

1. Core logic  
2. Logic-only libraries (this repository)  
3. Private strategies (TradingView)  
4. Execution & automation (external)

Only **layer 2** lives here.

## Philosophy

All libraries in this repository:
- use Pine Script v6
- are logic-only (`library()`)
- expose deterministic outputs
- hide proprietary thresholds internally

This repository is not intended for direct trading use.
