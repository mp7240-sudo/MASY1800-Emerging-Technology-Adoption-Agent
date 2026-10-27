# Assignment 6 step by step

1. Context established from earlier records: LLM intake assistant, hypothetical conservative regional bank, human advisor authority, 12-18 month horizon.
2. Initial specialist instructions and fixed evidence brief prepared. Review the recommendation categories and data/control assumptions.
3. Open work/adoption_agent_primary_prompt.txt. Paste the entire packet into a new normal ChatGPT conversation and save its unedited JSON answer as agents/adoption_agent/responses/primary_response_v1.json. Repeat in separate conversations for contrast_1 and contrast_2.
4. Validate each saved response using the original tool: python3 tools/validate_response.py agents/adoption_agent/responses/primary_response_v1.json (substitute the other filenames).
5. Compare the findings: general evidence should stay stable; posture may affect timing but cannot supply missing safeguards. Contrast 2 has explicit hypothetical readiness evidence and can justify a different stage.
6. Preserve and diagnose an actual weakness. Save the v0.1 instructions and original response before updating. Retest the unchanged case after revision.
7. Complete the supplied Agent Record from actual results. Student must confirm independent judgment; do not invent reflection, approvals, bank outcomes, or test provenance.
8. Commit final agent and evidence, record GitHub URL/branch/candidate commit in the Agent Record, and submit according to Brightspace. Repository setup alone is not a completed assignment.
