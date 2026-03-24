# Incremental Metrics Summary

- Generated at (UTC): 2026-03-24T11:44:37Z
- Sample count: 313
- Error rows: 0

## Overall

| Metric | Count | Mean/Rate | P50 | P95 |
| --- | --- | --- | --- | --- |
| completed_all_stages | 313 | 0.9968 |  |  |
| final_matches_reference | 313 | 0.1086 |  |  |
| canonicalized_match | 313 | 0.1118 |  |  |
| exact_update_count_match | 313 | 0.9968 |  |  |
| stage_coverage_rate | 313 | 0.9968 | 1.0 | 1.0 |
| node_semantic_f1 | 313 | 0.6714 | 0.8 | 1.0 |
| group_semantic_f1 | 313 | 0.8797 | 1.0 | 1.0 |
| edge_semantic_f1 | 313 | 0.6422 | 1.0 | 1.0 |
| attachment_semantic_f1 | 313 | 0.7444 | 1.0 | 1.0 |
| entity_semantic_f1 | 313 | 0.4584 | 0.4444 | 1.0 |
| updates_emitted | 313 | 2.5463 | 2.0 | 5.0 |
| total_stages | 313 | 2.5495 | 2.0 | 5.0 |
| planner_calls | 313 | 2.5463 | 2.0 | 5.0 |
| gate_latency_mean_ms | 313 | 2129.7949 | 2130.3554 | 2179.7783 |
| planner_latency_mean_ms | 312 | 24300.9486 | 17056.903 | 38458.8202 |
| total_model_latency_ms | 313 | 76963.4192 | 50721.6959 | 212677.5445 |

## By Diagram Type

| Diagram Type | Count | Final Match Rate | Canonicalized Match Rate | Entity Semantic F1 Mean | Coverage Mean | Planner Latency Mean Ms |
| --- | --- | --- | --- | --- | --- | --- |
| architecture | 54 | 0.0185 | 0.0556 | 0.3682 | 1.0 | 51877.71 |
| er | 51 | 0.0 | 0.0 | 0.4698 | 1.0 | 14918.5032 |
| flowchart | 52 | 0.2115 | 0.2115 | 0.4967 | 1.0 | 18434.4344 |
| mindmap | 53 | 0.3774 | 0.3396 | 0.7336 | 0.9811 | 15261.5336 |
| sequence | 51 | 0.0392 | 0.0588 | 0.2893 | 1.0 | 21164.302 |
| statediagram | 52 | 0.0 | 0.0 | 0.3876 | 1.0 | 22847.8117 |
