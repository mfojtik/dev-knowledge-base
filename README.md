# Developer Knowledge Base

This repository provide a base for sharing knowledge that help developers debugging issues or improve
daily life.

The list of possible articles in knowledge base include:

* [Prometheus](https://prometheus.io/docs/prometheus/latest/querying/basics/) queries
* Bash scripts or one liners
* Component debugging guides
* Post-mortems

## When to Create a New Article

Create new article here once you:

* Got a useful command/snippet that your or other team can use when debugging
* Investigated interesting problem and got steps that others might benefit
* Wrote a script that might help others
* Worked on incident or firedrill that affected others and need post-mortem

## Repository Structure

In order to keep articles organized, please use directory structure to group articles by topics:

* `./network`, `./apiserver`, `./etcd`... - articles related to specific component
* `./post-mortem/NAME/` - post-mortem articles, include scripts, logs, etc.
