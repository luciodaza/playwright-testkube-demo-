# playwright-testkube-demo

A minimal Playwright test suite, set up to run in [Testkube](https://testkube.io) as a Test Workflow.

## Run locally
```bash
npm ci
npx playwright install
npx playwright test
```

## Run in Testkube
This repo is referenced by a Testkube Test Workflow that checks it out, installs
dependencies, and runs the suite with tracing on. See the workflow YAML in the
video kit.
