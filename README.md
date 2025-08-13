# The Mascot API

[![Pipeline](https://github.com/automate6500/mascot-api/actions/workflows/pipeline.yml/badge.svg)](https://github.com/automate6500/mascot-api/actions/workflows/pipeline.yml)

The Mascot API is a Python application that serves JSON data over HTTP using the Flask framework.

The project also includes a really awesome pipeline with the following stages:

```mermaid
graph LR
    A[Lint and Test Application Code] --> B[Build Container Image]
    B --> C[Test Container Image]
    C --> D[Deploy to GCP Cloud Run]
```

:D
:D
