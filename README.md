# metameros-ai-agents

AI agents for author marketing workflows, media intelligence, and publishing analytics.

## Overview

`metameros-ai-agents` is the automation layer for Metameros.

This repository is designed to house modular AI agents that support:

- Amazon ranking analysis
- review summarization
- competitor intelligence
- keyword monitoring
- publishing workflow automation
- author marketing decision support

The goal is to create a system of specialized agents that can collect, interpret, and report on the signals that drive book discovery, launch performance, and long-term catalog growth.

## Core Agents

### 1. ranking-analyzer
Tracks and interprets Amazon performance signals such as:

- Best Seller Rank (BSR)
- category rank movement
- pricing shifts
- format performance
- launch velocity

### 2. review-summarizer
Processes reader reviews to identify:

- recurring praise points
- common complaints
- sentiment trends
- feature requests
- positioning opportunities

### 3. competitor-scout
Monitors comparable titles and author competitors by tracking:

- category placement
- pricing
- reviews
- metadata patterns
- launch positioning

### 4. keyword-monitor
Tracks keyword opportunities across Amazon and search behavior, including:

- keyword demand
- ranking changes
- trend velocity
- topic clusters
- discoverability signals

## Repository Structure

agents/      Individual agent definitions and configs
workflows/   Cross-agent operating workflows
schemas/     Structured data formats for outputs
docs/        Project architecture, roadmap, and vision
examples/    Example outputs and reports
