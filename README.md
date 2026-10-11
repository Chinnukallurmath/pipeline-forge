\# PipelineForge



A beginner-friendly DevOps capstone demonstrating a CI pipeline using GitHub Actions.



\## Project contents



\- `hello.sh`: Prints Hello, world!

\- `.github/workflows/ci.yaml`: Runs Build, Test, and Deploy jobs in order.



\## Workflow trigger



The workflow runs when a pull request targets the `main` branch.



\## Run locally



```bash

bash hello.sh

```



\## Pipeline sequence



Build -> Test -> Deploy



This project demonstrates pipeline ordering. The jobs print messages and do not deploy a real application.

Capstone status: Initial CI pipeline configured.
