# demo

Demonstration repository for Logtalk actions and workflows.
The source files are a copy of the `aliases` example in the Logtalk distribution.

![](https://github.com/logtalk-actions/demo/workflows/Testing/badge.svg)

The [`testing`](https://github.com/logtalk-actions/demo/blob/master/.github/workflows/testing.yml) workflow makes available a TAP report and a code coverage report as build artifacts. Navigate to the commits list, select the latest successful commit, and go into the build details (green check mark) to download the build artifacts. The code coverage report is also published to [https://logtalk-actions.github.io/demo/coverage_report.html](https://logtalk-actions.github.io/demo/coverage_report.html).

![](https://github.com/logtalk-actions/demo/workflows/Diagrams/badge.svg)

The [`diagrams`](https://github.com/logtalk-actions/demo/blob/master/.github/workflows/diagrams.yml) workflow makes available an application entity diagram in SVG format. Navigate to the commits list, select the latest successful commit, and go into the build details (green check mark) to download the diagrams.

![](https://github.com/logtalk-actions/demo/workflows/Documenting/badge.svg)

The [`documenting`](https://github.com/logtalk-actions/demo/blob/master/.github/workflows/documenting.yml) workflow makes available the application documentation in HTML format using Sphinx. Navigate to the commits list, select the latest successful commit, and go into the build details (green check mark) to download the documentation.
