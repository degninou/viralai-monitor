# viralai-monitor

Status page for the ViralAI full-protocol run on the Curta cluster (MCIA).

* Page: https://degninou.github.io/viralai-monitor/
* Machine-readable: https://degninou.github.io/viralai-monitor/status.json

`docs/` is regenerated on the Curta login node by `viralai_status.py` and pushed by
`viralai_publish.sh`. It carries job state and aggregate run metrics only; no
patient-level data is published here.
