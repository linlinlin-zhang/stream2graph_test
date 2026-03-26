# Incremental Metrics Summary

- Generated at (UTC): 2026-03-25T23:35:20Z
- Sample count: 312
- Error rows: 0

## Overall

| Metric | Count | Mean/Rate | P50 | P95 |
| --- | --- | --- | --- | --- |
| completed_all_stages | 312 | 0.984 |  |  |
| final_matches_reference | 312 | 0.0224 |  |  |
| canonicalized_match | 312 | 0.0513 |  |  |
| exact_update_count_match | 312 | 0.984 |  |  |
| stage_coverage_rate | 312 | 0.9884 | 1.0 | 1.0 |
| node_semantic_f1 | 312 | 0.4849 | 0.5714 | 1.0 |
| group_semantic_f1 | 312 | 0.8152 | 1.0 | 1.0 |
| edge_semantic_f1 | 312 | 0.6218 | 1.0 | 1.0 |
| attachment_semantic_f1 | 312 | 0.7028 | 1.0 | 1.0 |
| entity_semantic_f1 | 312 | 0.3325 | 0.359 | 0.8254 |
| updates_emitted | 312 | 2.5769 | 2.0 | 5.0 |
| total_stages | 312 | 2.6026 | 2.0 | 5.0 |
| planner_calls | 312 | 2.5769 | 2.0 | 5.0 |
| gate_latency_mean_ms | 312 | 3406.3634 | 3398.257 | 3694.5682 |
| planner_latency_mean_ms | 310 | 10153.832 | 8494.5166 | 21014.9857 |
| total_model_latency_ms | 312 | 51704.2734 | 42740.534 | 141114.7898 |

## By Diagram Type

| Diagram Type | Count | Final Match Rate | Canonicalized Match Rate | Entity Semantic F1 Mean | Coverage Mean | Planner Latency Mean Ms |
| --- | --- | --- | --- | --- | --- | --- |
| architecture | 52 | 0.0 | 0.0577 | 0.281 | 0.9808 | 13790.3491 |
| er | 53 | 0.0 | 0.0 | 0.4381 | 1.0 | 8488.8175 |
| flowchart | 52 | 0.0 | 0.1154 | 0.3808 | 0.9712 | 11870.3301 |
| mindmap | 53 | 0.0943 | 0.0566 | 0.3676 | 1.0 | 10064.4052 |
| sequence | 51 | 0.0392 | 0.0784 | 0.1872 | 1.0 | 7370.7963 |
| statediagram | 51 | 0.0 | 0.0 | 0.3349 | 0.9778 | 9407.0952 |
