# `demo`

Demonstration repository for Logtalk actions and workflows.
The source files are a copy of the `aliases` example in the Logtalk distribution.

![](https://github.com/logtalk-actions/demo/workflows/Workflow/badge.svg)

The [`workflow`](https://github.com/logtalk-actions/demo/blob/master/.github/workflows/workflow.yml) performs the following tasks:

- runs the tests and publishes TAP and code coverage reports
- (re)generates API documentation
- (re)generates file loading and entity diagrams

All results are automatically published to [https://logtalk-actions.github.io/demo/](https://logtalk-actions.github.io/demo/).

This workflow customizes and combines the individual steps of the testing, documenting, and diagramming sample workflows available at [https://github.com/logtalk-actions](https://github.com/logtalk-actions). The main reason to combine the workflows instead of running them individually and concurrently is to minimize processing requirements by setting up Logtalk and the used Prolog backend only once.
