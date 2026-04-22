# Scenario: Payment Flow and Shell Orders

## Problem

Previously, only successful orders were visible. Failed payment attempts were not properly captured.

## Why that mattered

This created problems for:
- reporting
- fraud checks
- tracking customer behaviour
- downstream system visibility

## BA thinking focus

- What is changing?
- What data needs to be captured?
- What happens if multiple payment attempts occur?
- How do we prevent corrupting main order data?
- What systems are dependent on this flow?

## Key trade-off

Speed of delivery versus system integrity.

## Learning point

A strong BA does not just gather requirements. They challenge the design, surface risks, and clarify ownership.
