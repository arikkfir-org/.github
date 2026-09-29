# arikkfir-org

A personal development hub: the home of personal projects, and of the platform they are built and run on.

- **Platform**: a single GKE cluster in `me-west1`, provisioned with Terraform ([infra](https://github.com/arikkfir-org/infra))
  and operated through GitOps with Argo CD ([delivery](https://github.com/arikkfir-org/delivery)).
- **CI**: [octomaton](https://github.com/arikkfir-org/octomaton), an application-agnostic GitHub App that runs the
  Tekton pipelines each repository declares in `.octomaton.yaml` and reports them as GitHub checks. No GitHub Actions.
- **Knowledge**: designs, architecture and runbooks live in [docs](https://github.com/arikkfir-org/docs), published
  (behind sign-in) at <https://docs.dev.kfirs.com/README.html>. Conventions are in
  [CONTRIBUTING](https://github.com/arikkfir-org/docs/blob/main/CONTRIBUTING.md).
- **Tooling**: shared developer tooling, such as the Claude Code bundle, lives in
  [tooling](https://github.com/arikkfir-org/tooling).
