---
title: "Two Patents on Breaking Self-Driving Cars (On Purpose)"
date: 2019-08-22 12:00:00 -0700
categories: [Publications, Patents]
tags: [patents, simulation, testing, autonomous vehicles]
image:
  path: /assets/img/av-testing-patents.png
  alt: Autonomous vehicle testing framework blueprint
---

I was granted two patents on autonomous vehicle testing. Both are about the same fundamental problem: how do you know a self-driving car is actually safe?

## The Problem

You can't test every possible scenario on real roads. There are too many variables — weather, pedestrians, other drivers, road conditions, edge cases you haven't even imagined yet. Physical testing is necessary but nowhere near sufficient.

So you simulate. But simulation has its own problem: infinite scenarios, finite time. You need to be smart about *which* scenarios you test.

## Patent 1: High-Value Test Generation

**US 20190271614**

This patent covers methods for finding the scenarios that actually matter — the edge cases and weird situations that are most likely to reveal problems. Instead of testing randomly, you test strategically.

The key insight: not all tests are created equal. A test that exercises a new code path is more valuable than one that repeats what you've already validated.

🔗 [View Patent →](https://patents.justia.com/patent/20190271614)

## Patent 2: Simulation and Testing Framework

**US 20190278698**

This patent covers the infrastructure for making simulation trustworthy. Sensor models, physics engines, scenario replay, and validation frameworks.

The key insight: simulation is only useful if it's realistic enough that passing tests actually means something in the real world.

🔗 [View Patent →](https://patents.justia.com/patent/20190278698)

## The Payoff

Nine years after these patents, I rode in a Tesla that drove itself coast-to-coast. The simulation frameworks we built — the ability to test millions of scenarios before deployment — are part of why that was possible.
