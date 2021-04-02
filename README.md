# Disable GCP App Engine

A simple tool to disable an App Engine default service.

## How to
- Install Google Cloud SDK: `brew install --cask google-cloud-sdk`
- Authenticate: `gcloud auth login`
- Checkout project: `gcloud config set project your-project-id`
- Deploy deletable dummy app: `gcloud app deploy`
- Done.