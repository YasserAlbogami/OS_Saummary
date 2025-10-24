# CPCS-361 — Operating Systems (Summary)

Concise summary of core topics from slides 1–8 for CPCS-361. The full styled content and quick interactive features are in [index.html](index.html).

## Quick start

- Open [index.html](index.html) in a browser.
- Use the "📋 Copy to Clipboard" button (DOM symbol: [`copyBtn`](index.html)) to copy the full summary (variable: [`originalContent`](index.html)).
- Use the "🖨️ Print" button (DOM symbol: [`printBtn`](index.html)) to print the document.
- Toggle the Table of Contents using the header (handlers: [`toggleTOC`](index.html), elements: [`tocHeader`](index.html), [`tocToggle`](index.html), [`tocContent`](index.html)).

## Topics covered

- Operating System fundamentals and structure
  - Roles: resource allocator and control program
  - Kernel, system programs, middleware
- OS perspectives: user view vs system view
- Key techniques: multiprogramming, timesharing, dual‑mode operation
- OS subsystems
  - Process management (PCB, process lifecycle, IPC: shared memory & message passing)
  - Threads (user vs kernel threads)
  - Memory and storage management (allocation, virtual memory, file systems, caching)
  - I/O management (drivers, buffering, spooling)
- CPU scheduling policies and schedulers
  - Long‑term, short‑term, medium‑term schedulers and the dispatcher
- Scheduling metrics and formulas
  - Turnaround time: $TAT = CT - AT$
  - Wait time: $WT = TAT - BT$
  - Throughput: total number of processes / total execution time
- Specific scheduling algorithms
  - FCFS, SJF, SRTF, Priority (with aging), Round Robin (time quantum $q$), Multilevel Queues (MLQ), Multilevel Feedback Queues (MLFQ)

## Accessibility & behavior notes

- Smooth scrolling for TOC links is implemented in [index.html](index.html).
- TOC toggle supports keyboard activation (Enter / Space) via [`tocHeader`](index.html) event handling.

## Author

Created by Yasser A. Albogami — profile linked inside the page header in [index.html](index.html).

## Files

- [index.html](index.html) — main document (styled summary + interactive script)
