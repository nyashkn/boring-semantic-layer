# Changelog

## Unreleased (nyashkn fork)

- Allow `ibis-framework` 12 (cap `<12` raised to `<13` in `pyproject.toml`). Fork-only change, not yet upstreamed.
- Verified on ibis 12.0.0 + pandas 3.0.6 + duckdb 1.5.6: unit suite has no new failures vs ibis 11 (995 passed; 27 failures are missing optional extras plus `test_error_handling_invalid_json`, which also fails on ibis 11).
- `tools/bsl` smoke test and real-data check pass (25 of 25 counts matched; MCP `query_model` works).
