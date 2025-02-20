# MicroShift in Container GitHub Action

This GitHub Action facilitates the deployment and management of [MicroShift](https://github.com/openshift/microshift) 
within a containerized environment, streamlining the process for continuous integration and deployment workflows using
[OKD](https://okd.io/) payload.


## Features

- **Automated Deployment**: Seamlessly deploy MicroShift in your CI/CD pipelines.
- **Containerized Environment**: Run MicroShift within a container, ensuring consistency across different environments.
- **Simplified Management**: Easily start, stop, and manage MicroShift instances as part of your GitHub workflows.

## Usage

To incorporate this action into your workflow, add the following step to your GitHub Actions workflow file:

```yaml
- name: Set up MicroShift
  uses: praveenkumar/minp-github-action@main
```

## Sample Example
- https://github.com/praveenkumar/simple-go-server/blob/main/.github/workflows/minp.yaml
