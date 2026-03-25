# Incremental Metrics Summary

- Generated at (UTC): 2026-03-25T19:04:57Z
- Sample count: 312
- Error rows: 0

## Overall

| Metric | Count | Mean/Rate | P50 | P95 |
| --- | --- | --- | --- | --- |
| completed_all_stages | 312 | 0.984 |  |  |
| final_matches_reference | 312 | 0.0737 |  |  |
| canonicalized_match | 312 | 0.0865 |  |  |
| exact_update_count_match | 312 | 0.984 |  |  |
| stage_coverage_rate | 312 | 0.9884 | 1.0 | 1.0 |
| node_semantic_f1 | 312 | 0.6291 | 0.75 | 1.0 |
| group_semantic_f1 | 312 | 0.8727 | 1.0 | 1.0 |
| edge_semantic_f1 | 312 | 0.6218 | 1.0 | 1.0 |
| attachment_semantic_f1 | 312 | 0.7661 | 1.0 | 1.0 |
| entity_semantic_f1 | 312 | 0.4385 | 0.4354 | 1.0 |
| updates_emitted | 312 | 2.5769 | 2.0 | 5.0 |
| total_stages | 312 | 2.6026 | 2.0 | 5.0 |
| planner_calls | 312 | 2.5769 | 2.0 | 5.0 |
| gate_latency_mean_ms | 312 | 3371.8454 | 3343.8347 | 3623.6745 |
| planner_latency_mean_ms | 310 | 20814.5974 | 17196.5098 | 39942.3487 |
| total_model_latency_ms | 312 | 82862.6571 | 55737.368 | 197873.5928 |

## By Diagram Type

| Diagram Type | Count | Final Match Rate | Canonicalized Match Rate | Entity Semantic F1 Mean | Coverage Mean | Planner Latency Mean Ms |
| --- | --- | --- | --- | --- | --- | --- |
| architecture | 52 | 0.0 | 0.0577 | 0.3885 | 0.9808 | 22261.6181 |
| er | 53 | 0.0 | 0.0 | 0.4646 | 1.0 | 14949.1324 |
| flowchart | 52 | 0.1923 | 0.25 | 0.4964 | 0.9712 | 21619.5724 |
| mindmap | 53 | 0.1698 | 0.1509 | 0.6354 | 1.0 | 19639.0965 |
| sequence | 51 | 0.0784 | 0.0588 | 0.2745 | 1.0 | 21457.1344 |
| statediagram | 51 | 0.0 | 0.0 | 0.3628 | 0.9778 | 25237.1472 |
