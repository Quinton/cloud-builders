# Tool builder: `gcr.io/cloud-builders/serverless`

This Cloud Build builder runs the `serverless` tool.

```yaml
steps:
- name: gcr.io/cloud-builders/serverless
  entrypoint: serverless
  args: ['depoly']
```

## Building this builder

To build this builder, run the following command in this directory.

$ gcloud builds submit . --config=cloudbuild.yaml
