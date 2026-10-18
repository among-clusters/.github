# Among Clusters

Among Clusters records auditable, least-privilege collaboration between
Kubernetes clusters while every participant retains authority over its own
credentials and runtime.

- Website: https://among-clusters.github.io/website/
- Public roadmap: https://github.com/orgs/among-clusters/projects
- Control plane: https://github.com/among-clusters/among-clusters
- Access contracts: https://github.com/among-clusters/connectool

GitHub is the coordination and event bus, not the runtime manager.

- Git and pull requests carry desired-state proposals and transitions.
- Kubernetes/K3s executes runtime state.
- Flux reconciles approved Git state.
- Headlamp provides lightweight runtime inspection.
- Prometheus, logs and traces remain in observability backends.
- GitHub Issues retain actionable events, decisions, evidence links and audit
  history, never bulk raw telemetry.

