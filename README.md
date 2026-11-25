# <Repo name>

<One paragraph in plain language: what this repository is for and which question it answers.>

Part of **NeuroPulse**, a final-year research project on structure-function-aware pruning for
continual learning. Project site: https://neuropulse-co.github.io · Organisation: https://github.com/NeuroPulse-Co

**Workstream:** W? <title> (see [workstreams](https://github.com/NeuroPulse-Co/.github/blob/main/standards/workstreams.yaml))

## Studies

| Study | Question | Status | Owner |
|---|---|---|---|
| [`<id>`](studies/<id>/) | <one line> | running | <name> |

## How to run

```bash
# setup
# a recorded run (writes run.yaml + console.log under $NP_OUTPUTS)
uv run tools/record.py run <study> --tag <tag> --seed 42 -- <command>
```

## How we keep records

We follow the [NeuroPulse record standard](https://github.com/NeuroPulse-Co/.github/blob/main/standards/RECORDS.md):
each study in `studies/<id>/` has a `study.yaml`, a `LOG.md` and one `runs/<run-id>/run.yaml` per run;
`showcase/` holds the curated pages the project website publishes. `uv run tools/record.py check`
validates everything and also runs in CI.
