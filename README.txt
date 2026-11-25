Magnetically Steered Cardiac Ablation
Amanda Pope and Bryton Lawson | Fall 2026

From this folder, install dependencies:
  python -m pip install -r requirements.txt

Run acceptance tests:
  python -m pytest -q

Run milestones (each saves its figure in figures/):
  python scripts/m1_navigation_field.py
  python scripts/m2_steering.py
  python scripts/m3_coil_budget.py
  python scripts/m4_tissue.py
  python scripts/m5_system.py

Optional warm-up: python scripts/m0_warmup.py

emlab/ contains the simulation implementations. tests/ contains the supplied tests.
PROJECT_HANDOUT.pdf is retained for reference. The report and design recommendation
are separate deliverables. Figure 4 uses the corrected two-by-two layout.
