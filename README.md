# Apify MCP connector article fixture

This repository is a deliberately small, non-deployable fixture for demonstrating a failure-aware dependency triage workflow:

1. an Apify Actor reads `package.json` through a GitHub MCP connector;
2. exact versions are checked against OSV;
3. the Actor creates or updates one review issue;
4. no dependency, branch, pull request, or production system is changed automatically.

The pinned versions are intentionally old so the public OSV database returns useful review evidence. Do not copy them into an application.

Article and Actor source: [Thirdwatch Apify Actors](https://github.com/poojitha-rachuri/apify-actors)
