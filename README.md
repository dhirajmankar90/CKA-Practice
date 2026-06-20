# CKA Practice

This repository contains Kubernetes manifest files used for Certified Kubernetes Administrator (CKA) practice and exercises.

## Contents

- `ConfigMap & Secrets/`
  - `cm.yaml` - ConfigMap example
  - `cmupdated.yaml` - Updated ConfigMap example
  - `deployment-cm.yaml` - Deployment using ConfigMap values
  - `deployment-secret.yaml` - Deployment using Secret values
  - `pod.yaml` - Pod manifest example
  - `secret.yaml` - Secret example
  - `svc-cm.yaml` - Service manifest exposing ConfigMap-backed pods
- `Deployment/`
  - `Untitled-3.yaml` - Additional deployment example or practice manifest

## Usage

Use `kubectl apply -f <file>` to deploy these resources to a Kubernetes cluster.

Example:

```bash
kubectl apply -f "ConfigMap & Secrets/cm.yaml"
kubectl apply -f "ConfigMap & Secrets/secret.yaml"
kubectl apply -f "ConfigMap & Secrets/deployment-cm.yaml"
```

## Notes

- Update paths and resource names as needed for your cluster environment.
- Keep secrets secure and avoid committing sensitive data directly to version control.
