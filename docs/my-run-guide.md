# My Run Guide

## Prerequisites
- JDK 17 or later (`java` and `javac` on PATH)
- Python 3.9 or later

## Run the demo
    python3 run.py demo

## What the demo does
It compiles the Java code and runs a small library scenario with a fixed
date (2026-09-01): it shows the borrowing limits (2 per member), searches
the catalog for "git" (no result in this baseline), lends "Git Essentials"
to Alex (due 2026-09-15), then returns it with a fee of 0 and no active loans left.