# Link-audit fixture

This file exists to exercise a failure-aware documentation audit through an Apify GitHub MCP connector.
Production evidence pins this file to an immutable commit before the Actor reads it.

- Reachable project page: <https://apify.com/>
- Reachable repository: <https://github.com/poojitha-rachuri/apify-mcp-connector-fixture>
- Deliberate 404 for repeatable evidence: <https://example.com/thirdwatch-apify-mcp-link-audit-missing>
- Deliberate unsafe target that must be rejected before any request: <http://127.0.0.1:8080/admin>

The last two entries are test fixtures. They are not recommendations or production dependencies.
