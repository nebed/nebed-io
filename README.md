# Nebed.io

Minimalist DevOps portfolio website.

## Local Development

1. Install Hugo: `brew install hugo`
2. Run server: `hugo server -D`

## Deployment

Pushes to `main` trigger a GitHub Action that builds and deploys to GCS bucket `nebed-io`.
