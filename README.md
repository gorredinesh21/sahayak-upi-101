# UPI Payments 101 — visual crash course for Sahayak

Four-page explainer site used to design and pitch Sahayak:
- `index.html` — UPI from zero: players, animated payment journey, message vs
  money, field guide, NPCI response codes, 4 failure scenes, backtracking.
- `reality.html` — why support humans exist, the anxiety gap, automatability,
  market numbers, strategies, engine room (Vertex Gemini + Sarvam + Cognee).
- `engines-deep.html` — architecture map, what Cognee is, the agent loop code.
- `data-protocol.html` — the build spec: log tables with exact columns, triage
  router, the 3 modes' protocols, data provenance.

Live: https://sahayak-upi-101-yzzxrxetcq-uc.a.run.app (Cloud Run, nginx).
Deploy: `gcloud run deploy sahayak-upi-101 --source . --region us-central1 \
  --project personal-project-dg21 --allow-unauthenticated`
