# Port-Scanner — Educational Network Tool

A small, classroom-safe **port analyser** implemented in Java (simulation).  
This repository contains an **educational, non-intrusive Java implementation** that demonstrates scanning output formats, simple banner-like identification, concurrency-style behavior, and export/reporting — **without performing any real network probing**. Use it for labs, reports, and demonstration only.

## Features
- Accepts a single port or a port range (e.g., `20-1024`)  
- Deterministic simulated open/closed results per target+port (repeatable for demos)  
- Simulated banner identification for common services (ssh, http, mysql, etc.)  
- Verbose and compact console output modes for realistic behavior  
- Optional CSV and JSON export for reporting  
- Plain Java (JDK 8+) with no external libraries required

## Tech / Languages
- Java (primary implementation)  
- Standard Java I/O and collections — no external jars required

## Usage (examples)
> **Ethical notice:** This repo provides a **simulation only**. Do **not** perform network scans without explicit written permission. Unauthorized scanning may be illegal.

**Compile**
```bash
javac SimulatedPortScanner.java
