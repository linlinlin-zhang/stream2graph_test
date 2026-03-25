# Incremental Metrics Summary

- Generated at (UTC): 2026-03-25T11:32:42Z
- Sample count: 312
- Error rows: 0

## Overall

| Metric | Count | Mean/Rate | P50 | P95 |
| --- | --- | --- | --- | --- |
| completed_all_stages | 312 | 0.9904 |  |  |
| final_matches_reference | 312 | 0.0321 |  |  |
| canonicalized_match | 312 | 0.0577 |  |  |
| exact_update_count_match | 312 | 0.9904 |  |  |
| stage_coverage_rate | 312 | 0.9933 | 1.0 | 1.0 |
| node_semantic_f1 | 312 | 0.506 | 0.6 | 1.0 |
| group_semantic_f1 | 312 | 0.8156 | 1.0 | 1.0 |
| edge_semantic_f1 | 312 | 0.6218 | 1.0 | 1.0 |
| attachment_semantic_f1 | 312 | 0.701 | 1.0 | 1.0 |
| entity_semantic_f1 | 312 | 0.3452 | 0.3587 | 0.9429 |
| updates_emitted | 312 | 2.5865 | 2.0 | 5.0 |
| total_stages | 312 | 2.6026 | 2.0 | 5.0 |
| planner_calls | 312 | 2.5865 | 2.0 | 5.0 |
| gate_latency_mean_ms | 312 | 2163.8465 | 2139.6937 | 2368.6855 |
| planner_latency_mean_ms | 311 | 10405.6734 | 8463.9404 | 22818.5133 |
| total_model_latency_ms | 312 | 47711.8523 | 34003.1075 | 152942.4817 |

## By Diagram Type

| Diagram Type | Count | Final Match Rate | Canonicalized Match Rate | Entity Semantic F1 Mean | Coverage Mean | Planner Latency Mean Ms |
| --- | --- | --- | --- | --- | --- | --- |
| architecture | 52 | 0.0385 | 0.0769 | 0.3091 | 1.0 | 13720.822 |
| er | 53 | 0.0 | 0.0 | 0.4577 | 1.0 | 8049.1273 |
| flowchart | 52 | 0.0 | 0.1154 | 0.3693 | 0.9712 | 12438.6714 |
| mindmap | 53 | 0.1132 | 0.0755 | 0.3872 | 1.0 | 10924.6659 |
| sequence | 51 | 0.0392 | 0.0784 | 0.1872 | 1.0 | 7447.8616 |
| statediagram | 51 | 0.0 | 0.0 | 0.3547 | 0.9882 | 9859.9499 |
