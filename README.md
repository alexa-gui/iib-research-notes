# IIB Field Notes — public site bundle

This isolated source directory contains only the generated static research website under `dist/`. It intentionally excludes model checkpoints, private weights, source datasets and repository-only experiment artefacts.

The canonical website source remains `tools/site_template.tpl` plus the content under `research/`. Rebuild the main site first, then refresh this bundle from `site/` before deployment.
