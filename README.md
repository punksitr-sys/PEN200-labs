# PEN200-labs

Personal notes from 145 labs completed while preparing for PEN-200 and OSCP. The write-ups record the evidence behind each decision, including dead ends and the observations that prompted a change of direction.

## Guide and command reference

- [Lab Guide](1.1%20summary/1.1.8%20lab%20guide.md) — Use it when you're unsure what to check next. It explains how to turn observations into a lead, diagnose a failed test, decide when to move on, and document what you verified.
- [Command Reference](1.1%20summary/1.1.9%20command%20reference.md) — Use it when you already know which check you need. Commands are grouped by task and system, with notes on results that are easy to misread.

## Lab notes

| Collection | Notes |
| --- | ---: |
| [Capstone Labs](1.4%20capstone%20labs/) | 62 |
| [Proving Grounds](1.5%20pg%20labs/) | 36 |
| [Hack The Box](1.7%20htb%20labs/) | 47 |

Revisiting a completed lab? Start with its **Recap**, then follow the screenshots and troubleshooting notes to see why each lead was pursued or set aside. The write-ups contain spoilers.

## Selected write-ups

| Lab | Why read it |
| --- | --- |
| [TheFrizz](1.7%20htb%20labs/1.7.112%20TheFrizz%20%28Medium%29.md) | SSH still failed after the clocks were aligned. The next round of troubleshooting uncovered a separate hostname resolution issue. |
| [Sumo](1.4%20capstone%20labs/1.4.514%20Sumo.md) | One test failed to compile. Another ran but produced no useful result. The note shows why those outcomes called for different checks. |
| [Jacko](1.5%20pg%20labs/1.5.107%20Jacko.md) | An unstable Windows session made the output hard to interpret. Reviewing the service configuration gave a separate path to investigate. |
| [Timelapse](1.7%20htb%20labs/1.7.105%20Timelapse.md) | A certificate bundle and a service account raised different access questions. The note traces which account or group had the relevant permissions. |
| [Clicker](1.7%20htb%20labs/1.7.408%20Clicker%20%28lin%29.md) | One privileged script exposed three distinct trust boundaries involving the Perl environment, XML parsing, and shared library loading. |
