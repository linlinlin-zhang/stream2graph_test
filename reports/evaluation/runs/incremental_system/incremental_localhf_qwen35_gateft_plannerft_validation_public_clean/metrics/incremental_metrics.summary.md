# Incremental Metrics Summary

- Generated at (UTC): 2026-03-25T11:52:56Z
- Sample count: 312
- Error rows: 0

## Overall

| Metric | Count | Mean/Rate | P50 | P95 |
| --- | --- | --- | --- | --- |
| completed_all_stages | 312 | 0.9904 |  |  |
| final_matches_reference | 312 | 0.0865 |  |  |
| canonicalized_match | 312 | 0.0962 |  |  |
| exact_update_count_match | 312 | 0.9904 |  |  |
| stage_coverage_rate | 312 | 0.9926 | 1.0 | 1.0 |
| node_semantic_f1 | 312 | 0.6542 | 0.7692 | 1.0 |
| group_semantic_f1 | 312 | 0.8798 | 1.0 | 1.0 |
| edge_semantic_f1 | 312 | 0.6218 | 1.0 | 1.0 |
| attachment_semantic_f1 | 312 | 0.766 | 1.0 | 1.0 |
| entity_semantic_f1 | 312 | 0.4567 | 0.4593 | 1.0 |
| updates_emitted | 312 | 2.5833 | 2.0 | 5.0 |
| total_stages | 312 | 2.6026 | 2.0 | 5.0 |
| planner_calls | 312 | 2.5833 | 2.0 | 5.0 |
| gate_latency_mean_ms | 312 | 2220.0918 | 2217.5073 | 2468.4174 |
| planner_latency_mean_ms | 311 | 22576.5692 | 17215.378 | 44257.6475 |
| total_model_latency_ms | 312 | 85299.7353 | 50556.2151 | 237281.139 |

## By Diagram Type

| Diagram Type | Count | Final Match Rate | Canonicalized Match Rate | Entity Semantic F1 Mean | Coverage Mean | Planner Latency Mean Ms |
| --- | --- | --- | --- | --- | --- | --- |
| architecture | 52 | 0.0577 | 0.0962 | 0.4177 | 1.0 | 32129.8903 |
| er | 53 | 0.0 | 0.0 | 0.4734 | 1.0 | 14536.0837 |
| flowchart | 52 | 0.1923 | 0.25 | 0.5036 | 0.9712 | 23275.7548 |
| mindmap | 53 | 0.1887 | 0.1698 | 0.6799 | 1.0 | 18006.7345 |
| sequence | 51 | 0.0784 | 0.0588 | 0.2745 | 1.0 | 22493.4791 |
| statediagram | 51 | 0.0 | 0.0 | 0.3814 | 0.9843 | 25324.6752 |
