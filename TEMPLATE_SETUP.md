# After creating a repository from this template

1. In `README.md`, replace every `<...>` placeholder: the repo name, the one-paragraph purpose, and the workstream.
2. In `showcase/manifest.yaml`, set `repo:` to the new repository's name, or run
   `uv run tools/record.py check --fix-manifest`.
3. Create your first study:
   `uv run tools/record.py new <study-id> --workstream Wn --owner "Your Name"`
4. Add the repository to `registry.yaml` in NeuroPulse-Co.github.io, so the website reads its `showcase/`.
5. Run `uv run tools/record.py self-update` to make sure the tool and standards are current.
6. Delete this file.
