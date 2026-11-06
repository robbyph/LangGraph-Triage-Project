# LangGraph Alert Triage Project

This project builds a deterministic security-alert triage agent using Python
and LangGraph. It evaluates 12 synthetic, labelled alerts and measures caught
incidents, missed incidents, and unnecessary escalations across different
keyword settings. A second graph adds an approval-checking node backed by a
simulated lookup tool. With the same seven keywords, this addition reduces
unnecessary escalations from two to zero while preserving five caught
incidents and one missed incident. The notebook also demonstrates conditional
routing, checkpoint memory by thread identifier, and execution traces.
These results describe a small constructed dataset, not production performance.

## Running the notebook

Tested with Python 3.11.5. Create or select a Python environment and install the
packages in requirements.txt with `python -m pip install -r requirements.txt`.
Open agent_notebook.ipynb in VS Code or Jupyter, select that environment as the
kernel, and run every cell from top to bottom with this folder as the working
directory. The saved notebook includes all outputs.

Keep alerts.json beside the notebook: Parts 1-8 use the instructor's supplied
alerts, while Part 9 uses my_alerts.json. Running the notebook regenerates
results.csv, results_mine.csv, and SOURCES.md. The final results_mine.csv contains
10 keyword experiments and two graph-comparison rows.

The approval lookup is a simulated text-based scope check. It does not validate
live tickets, timestamps, or identities. The separate memory demonstration uses
an in-memory checkpointer on the original graph; restarting the kernel clears it.
